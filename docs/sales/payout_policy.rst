.. _payout_policy:

Payout Policy
=============

Whether a project is earning money through sales of *Products*, the *Payroll system* or a combination of both, Crowdsourcer.io will automatically distribute earnings to all members of a project, whether they're the creator or contributing members.

After the end of each month (1st of each month) payout will be performed and includes:

- Sales made up to the start of the month just ended [#f1]_. (i.e. Sales will be paid out as soon as 28 days, and at most 61 days after they're made).
- Refunds made up to the date of payout (decreases payout amount).
- Payrolls made up to the last 14 days.

The contribution split associated with each of the above is as follows:

- Sales: The contribution built up by the end of the previous month that the Sale was made in [#f2]_.
- Refunds: Simply matches the contribution split of the original Sale.
- Payrolls: The contribution built up by the end of the previous month that the Payroll was made in [#f2]_.

These rules are in place to protect all members of a project and to give ample time to resolve any conflicts arising from the accumulation of :ref:`contribution_basics`, before those Contribution Points start earning money.

In situations where Sales or Payrolls are made within the the first month of C.Pts being earned, the contribution split will be based on the contribution built up by the end of the month of that Sale or Payroll [#f3]_. This still gives at least 28 days for conflict resolution which is twice the length of time that a completed task can be sent to review after being completed. After this first month, normal contribution splits apply as above.

.. rubric:: Examples

.. [#f1] A sale made on the 15th of June will be included in the payout run the 1st of August.
.. [#f2] A sale/payroll dated the 15th of June will be split based on the contribution accumulated up to (but not including) the 1st of June.
.. [#f3] If the first Contribution points were earned on the 1st of June, a sale/payroll dated the 15th of June will be split based on the contribution accumulated up to (but not including) the 1st of July. This will only happen for that first month, so a sale/payroll dated the 15th of July will also be split based on the contribution accumulated up to (but not including) the 1st of July.

Payout Failure
---------------

Should a payout fail to be made to an individual, the user will receive an email with a reason for each project that failed to be paid out. If you've missed the email you can always view a log of payouts from your `Account <https://crowdsourcer.io/user-account/payout-log>`_.

There are many reasons why a payout to an individual may fail. Some of these reasons are listed below.

- The User has not linked a merchant account so cannot be paid out.
- The Project has negative payout amounts (from too many Refunds).

  * When sales are made, Crowdsourcer.io collects payments in a couple of currencies. It only takes one to be negative to prevent payout.
  * Overall outstanding refund amounts are greater than or equal to outstanding sales amounts.

- The Project has been prevented from receiving payouts (imposed by Crowdsourcer.io).

  * If the Project has failed conflict resolution.
  * If there has been a breach of the Terms and Conditions of the site.

- The User has been prevented from receiving payouts (imposed by Crowdsourcer.io).

  * If the User has an account ban.
  * If there has been a breach of the Terms and Conditions of the site.