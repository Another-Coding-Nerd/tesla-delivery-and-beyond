# Trade-In Considerations

If you're trading in a vehicle, do the math before you commit to a path —
the convenience gap and the tax math together often close more of the price
delta than it looks at first glance.

## Do the Math First

Tesla will almost certainly offer less than CarMax, Carvana, or a private
buyer. But the sticker delta isn't the real delta. Run this before deciding:

1. **Get a competing offer** — CarMax or Carvana first, before you contact
   Tesla about a trade-in. This gives you the actual spread to work with.

2. **Calculate the tax difference** — in most US states, trading in through
   the dealer means you pay sales tax only on the *difference* between the
   purchase price and the trade-in value. Selling externally means you pay
   tax on the full purchase price.

   Example at 8% sales tax:
   - Tesla trade-in at $17k on a $50k car → taxable amount $33k → tax $2,640
   - CarMax sale, buy outright → taxable amount $50k → tax $4,000
   - **Tax savings from Tesla trade-in: ~$1,360**

   The applicable rate and whether your state uses net-price taxation varies —
   verify for your state before finalizing the comparison.

3. **Factor in any Tesla trade-in promotion** — Tesla has offered 2,000 free
   Supercharger miles (~$225 value) for trading in a gas vehicle. Verify
   what's currently on offer at order time; promotions change.

4. **Calculate the real delta:**

   ```
   CarMax offer
   − Tesla trade-in offer
   − tax savings from trading through Tesla
   − value of any Tesla trade-in promotion
   = true out-of-pocket difference
   ```

   In the example above: $22k − $17k − $1,360 − $225 = **~$2,415** real
   difference, not the $5k headline gap.

5. **Weigh that number against the convenience cost** — if the real delta
   is small, Tesla's trade-in is hard to beat on logistics alone.

---

## Path A: Tesla Trade-In

- [ ] Submit your trade-in vehicle details through the Tesla app or website
      to get Tesla's offer.
- [ ] Confirm what trade-in promotions are currently active (free
      Supercharger miles, etc.) — ask your delivery advisor.
- [ ] Drop off the trade-in and pick up the new car in a single trip.
- [ ] Confirm the trade-in credit appears correctly on your final purchase
      agreement before signing.

---

## Path B: External Sale (CarMax, Carvana, etc.)

This path pays more but requires you to manage two transactions on separate
timelines.

### Timing the sale

The core problem: CarMax and Carvana offers are typically valid for **7
days**. Tesla deliveries slip. If you sell too early, you're without a car
before your Tesla arrives. If you wait for a confirmed delivery date, the
offer may have expired.

**The right trigger: the design lock status change.**

Once your Tesla order status changes from "Edit Design" to "You cannot edit
design at this time," your car is in production. A VIN typically appears in
your account shortly after, and delivery tends to move fast from that point
(see `01-pre-delivery.md`). That's the signal to go get your external offer.

- [ ] **Do not sell your car before the design lock status change** —
      delivery timelines are unreliable before that point; you could be
      without a vehicle for weeks.
- [ ] Once that status appears (or your VIN is assigned, whichever you
      notice first), get your CarMax/Carvana offer immediately — the 7-day
      clock starts then.
- [ ] Confirm your Tesla delivery appointment is within that 7-day window
      before selling. If it isn't, wait — you can get a fresh offer closer
      to your actual delivery date. Keep in mind you'll also be without a
      car during any gap, and floating on ride-shares beyond ~10 days gets
      expensive fast.
- [ ] **Don't cancel insurance on your current car until you have the
      Tesla in hand** — gap in coverage is expensive to reinstate, and
      continuous coverage typically qualifies for a longevity discount
      with your insurer. Once your Tesla VIN is assigned, call your
      insurance company and add the new vehicle — you'll need coverage
      in place before you can take delivery anyway. Cancel the old
      car's policy only after you've physically taken possession of
      the new one.

### The sale itself

- [ ] **Plan for a multi-day hold on the payment check** — CarMax and
      Carvana typically pay by cashier's check, which federal rules
      (Reg CC) make available next business day in theory. In practice,
      banks can hold the excess over ~$6,700 on large deposits for up
      to 7 business days. On a $17–22k car sale, most of the funds
      could be held that long. Confirm your bank's hold policy before
      you sell so there are no surprises.
- [ ] Arrange a ride home from CarMax after the sale — you'll need one.
- [ ] Arrange a ride to Tesla for pickup — you'll need one of those too.
- [ ] Confirm your Tesla delivery appointment timing accounts for any gap
      between selling your car and picking up the new one.

---

## Sources

- [How Long for a Check to Clear — Bankrate](https://www.bankrate.com/banking/checking/how-long-for-check-to-clear)
- [Understanding Funds Availability Rules — SoFi](https://www.sofi.com/learn/content/understanding-funds-availability)
- [Regulation CC Check Holds Explained — Beancount](https://beancount.io/blog/2026/09/09/regulation-cc-check-holds-exception-hold-small-business-cash-flow-guide)
