# Stakeholder Problem and Success Criteria

## Stakeholder, decision and question

The primary stakeholder is the hotel revenue manager. The manager needs to decide which booking groups should be prioritised when monitoring cancellation risk and planning room availability.

**Research question:** Which booking characteristics are associated with cancellation or no-show, and which booking groups have higher rates of these outcomes?

The target is `is_canceled`. A value of 1 represents a booking with a final status of `Canceled` or `No-Show`, while 0 represents `Check-Out`. In this dataset, 37.04% of bookings have a target value of 1. `reservation_status` and `reservation_status_date` will not be used as explanatory variables because they reveal the final outcome and would cause data leakage.

## Useful-answer criteria

A useful answer will identify clear and interpretable differences in cancellation rates across relevant booking characteristics. Comparisons should include both the number of bookings and the cancellation rate so that conclusions are not based on very small groups. The findings should help the revenue manager identify booking groups that may require greater attention.

## Cost of a misleading conclusion

A misleading conclusion could cause the hotel to focus on the wrong bookings, wasting staff time and unnecessarily inconveniencing guests who are likely to complete their stays. It could also cause the hotel to overlook bookings more likely to be cancelled or become no-shows, reducing its ability to plan room availability and resell rooms.

These results show associations rather than causes. Variables such as country and agent should be interpreted carefully, and findings from two Portuguese hotels in 2015–2017 may not apply to other hotels or current booking patterns.