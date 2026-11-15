# Cadence

An online course platform where learners buy courses, watch lessons, and can ask for their money back shortly after buying.

## Language

### Buying

**Purchase**:
A payment made for a course, either by a learner for themselves or by a team buyer for Team Seats.
_Avoid_: Order, transaction

**Team Seat**:
One place on a team's Purchase that a single learner can take to get access to the course.
_Avoid_: Coupon, licence

**Claimed**:
A Team Seat that a learner has taken. A learner on a Claimed Team Seat has no Purchase of their own.
_Avoid_: Redeemed

### Getting money back

**Refund Request**:
A learner's ask, with a written reason, to get their money back for a Purchase. It is Pending, Approved, or Declined.
_Avoid_: Reversal, Chargeback, Cancellation, cancel my purchase

**Review**:
An admin's decision to Approve or Decline a Pending Refund Request. Every Refund Request is reviewed by a person.
_Avoid_: Resolve

**Pending**:
The status of a Refund Request nobody has decided on yet.
_Avoid_: Requested, open, raised

**Approved**:
The status of a Refund Request that was granted, which results in a Refund and ends the learner's access to the course.

**Declined**:
The status of a Refund Request that was turned down. Nothing is refunded and access continues.
_Avoid_: Declined refund, rejected

**Refund**:
Money sent back to a learner as the result of an Approved Refund Request. A Refund only exists once the request is Approved.
_Avoid_: Reversal

**Refund Amount**:
What the learner actually paid for the Purchase, after any coupon or purchasing-power discount. Never the course's list price.

**Refund Eligibility**:
Whether a Purchase can still have a Refund Request made against it: within the Refund Window, under 2 hours watched, under half of the course's lessons completed, not a Claimed Team Seat, and no Pending Refund Request already open.

**Refund Window**:
The 14 calendar days after a Purchase, counted in whole days and including the 14th day in full.
