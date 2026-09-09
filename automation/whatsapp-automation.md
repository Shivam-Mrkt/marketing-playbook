# WhatsApp automation

## Objective

Support expected, opted-in conversations such as appointment reminders and requested follow-up. A phone number in the CRM is not sufficient permission to start a WhatsApp marketing sequence.

## Operating boundaries

WhatsApp's policy requires recipients to have provided their number and opted in to subsequent messages or calls. Respect opt-outs. For the Business Platform, check current template and customer-service-window rules before sending: approved templates are required for initiating conversations, and free-form replies are allowed within the 24-hour window after the user's last message. [WhatsApp Business Messaging Policy](https://whatsappbusiness.com/policy/).

These are platform requirements; the business must also determine the applicable local communication requirements. Avoid hard-coding prices or template eligibility into a durable playbook because they can change.

## Workflow

Recorded opt-in → Relevant event → Check purpose and messaging eligibility → Send approved message → Handle reply → Update CRM → Stop on opt-out

## Illustrative example: EdTech

Fictional CourseHarbor offers a WhatsApp reminder for a counselling session. The person chooses this channel during booking; the record stores the wording, time and source of that choice.

**Message concept:** “Your CourseHarbor course-advice session is tomorrow at 6 pm IST. Reply if you need to reschedule.” This concept must use the appropriate approved template when required. It does not add an unrelated course promotion to a service reminder.

If the person replies with a complex eligibility question, a human adviser takes over. The automation stops further reminders after cancellation or an opt-out.

## Step-by-step process

1. Define the specific message purpose and expected audience.
2. Capture and retain the appropriate opt-in evidence.
3. Confirm message category, template status and timing rules in the live platform.
4. Include a simple way to stop messages and a human support route.
5. Test cancellation, duplicate booking, reply and opt-out paths.
6. Monitor negative feedback and pause the flow if expectations are being missed.

## Metrics and checklist

Measure attended appointments, successful reschedules, reply resolution, opt-outs and delivery failures. Read rate alone is not the outcome.

- [ ] Opt-in evidence exists for the intended purpose.
- [ ] Current platform requirements checked.
- [ ] Timing uses the recipient's relevant time zone.
- [ ] Human handoff and cancellation paths work.

**Experiment idea:** compare one reminder timing with another among eligible bookings, measuring attendance and negative feedback.

Related: [Lifecycle marketing](../crm/lifecycle-marketing.md) · [CRM workflows](../crm/crm-workflows.md) · [Automation](README.md).
