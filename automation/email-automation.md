# Email automation

## Objective

Deliver relevant messages at useful moments while respecting lifecycle stage, contact preferences and replies. A timed sequence should not continue after the situation changes.

## Workflow framework

Eligible trigger → Check preferences and stage → Send useful message → Wait → Recheck status → Continue, hand off or exit

| Element | Decision |
| --- | --- |
| Trigger | Which observable action starts the journey? |
| Eligibility | Is this person eligible for this purpose and channel? |
| Content | What useful job does this message do? |
| Delay | Why is this interval appropriate? |
| Exit | Which response or stage change ends the journey? |
| Exception | Who handles failed delivery or unclear status? |

## Illustrative example: B2B SaaS

For a fictional RelayDesk resource request, the first message delivers the worksheet. If eligible for further marketing, a day-3 email explains one assignment-rule example. A day-7 message offers an optional review. A reply, demo request, opt-out or open opportunity stops the automated promotional journey and alerts the owner as appropriate.

The requested resource should not be withheld until someone agrees to unrelated nurture. Contact eligibility must follow the organisation's approved requirements for the audience and jurisdiction.

## Step-by-step process

1. Write entry, exclusion and exit rules before the copy.
2. Keep requested delivery distinct from optional promotional follow-up.
3. Check from-name, links, mobile layout and reply handling.
4. Recheck eligibility before every send, not only at enrolment.
5. Test duplicate triggers, stage changes, opt-outs and out-of-office responses.
6. Review failed sends and unexpected enrolments after activation.

## Metrics and mistakes

Track meaningful clicks, replies, qualified progression, unsubscribes and complaints. Opens can be affected by privacy tools and automated activity; do not use them alone to score or accelerate a prospect. Avoid overlapping journeys with contradictory offers.

## Practical checklist

- [ ] Entry and exit conditions are explicit.
- [ ] Every message has a useful purpose.
- [ ] Replies reach a monitored inbox.
- [ ] Suppression is checked at send time.
- [ ] Test contacts cannot reach live sales reporting.

**Experiment idea:** compare a worked example with a generic product introduction in the second message, measuring qualified next-step actions.

Related: [Lifecycle marketing](../crm/lifecycle-marketing.md) · [Follow-up sequences](../outbound/follow-up-sequences.md) · [Automation](README.md).
