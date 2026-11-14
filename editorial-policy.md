# intentinfrastructure.com — editorial and neutrality policy

The rules for what the site lists and how it shows it. They are written before
the first entry exists, so that they apply to Magnitude exactly as to everyone
else. Magnitude publishes the site; that is why it has to be neutral.

---

## 1. Scope — what "intent infrastructure" means here

**Intent infrastructure** is the layer that carries what a person or business
intends to do with their money **from the moment income lands to the moment
it is spent and settled: from paycheck to checkout** (D6). Once income lands,
it is inside intent infrastructure; earning it and processing payroll come
before. **The intent
is the human's, not the agent's** (D5). Agentic commerce, AI agents buying for
people, sits at the downstream end, at checkout. It is part of this layer, not
the whole of it.

The site's categories follow the money along that timeline, plus two that cut
across all of it. A product may sit in more than one.

| Category | Where on the timeline | What belongs in it |
|---|---|---|
| Allocation | When income lands | Money the person gives a purpose to as it arrives, where that purpose is then enforced: split deposits, segregated pots, envelopes or reserves that the spending path respects. Budgets that only track beside the account are out (the intent test). |
| Intent expression | Before a purchase | How a goal, preference or limit is captured in a form a system can act on: mandates, intent schemas, preference stores. |
| Agent identity and authorization | Before a purchase | Who may act on the intent: agent credentials, delegated authority, spending limits, consent records. |
| Payments and checkout | At the purchase | Paying in a way that carries the person's intent: credentials scoped to an intent, funding-source routing, agent-usable cards and tokens, wallets, rails, checkout APIs. |
| Trust, risk and recourse | After the purchase | What happens when a purchase doesn't match the intent: fraud and risk scoring, liability, disputes and refunds. |
| Merchant and catalog readiness | Across | Making merchants, products and prices consumable by agents and by intent-aware payments. |
| Protocols and standards | Across | Open specifications that connect the categories above, whoever maintains them. |

**Out of scope:**

- General assistants, chatbots and model providers, unless they ship a
  commerce or intent component, in which case that component is listed.
- General agent frameworks with no commerce or intent component.
- Budgeting, tracking and categorising tools whose plan never reaches the
  money (D7).
- Generic savings automation with no purpose stated by the person.
- Payment products that move money without carrying any stated intent of
  the person paying.
- B2B marketing "intent data" (buyer-intent signals sold to sales teams). Same
  word, different meaning. Decision D1.

---

## 2. Inclusion — what gets a product listed, and what takes it off

A product is listed when **all** of these hold:

0. **It passes the intent test** (D7). Both parts:
   - **A person states it.** A person or business says, explicitly, what
     specific money is for or what may be done with it: a purpose, a limit,
     a merchant, an account, an approval.
   - **It holds when money moves.** The product carries that statement into
     the movement of money, or proves or records it there: it enforces it,
     scopes a credential to it, routes by it, or checks against it.

   A plan that lives beside the account and never touches the money fails.
   So does a rail that moves money with no statement from the person.
1. It fits at least one category in section 1.
2. It exists publicly: shipping, in public beta, or a published specification.
   **Or it is pre-launch (D10):** announced by its maker in a primary source,
   but not yet usable. A pre-launch entry is labelled as such and appears only
   when the reader includes pre-launch. A product in stealth with no public
   word from its maker can't be listed, because there is nothing to cite.
3. There is at least one **primary source**: the maker's own docs, spec,
   repository, pricing page or official announcement. Press coverage alone
   does not qualify.
4. The maker is identifiable: a named company, project or standards body.

Nothing else affects inclusion. No payment, partnership, investment,
competitive position or relationship with Magnitude can add or remove a
listing.

**A listing changes status when:**

- **Discontinued:** the maker says so, or the product is gone. The entry is
  marked *Discontinued* and kept for 12 months, then archived.
- **Unverified:** its primary sources are dead or contradict the entry and it
  cannot be re-verified. It is marked *Unverified* until it is.
- **Out of scope:** the product changed and no longer fits a category. It is
  removed, with a line in the public changelog.

---

## 3. Neutrality — how every entry is shown

**One template.** Every entry has the same fields, the same length limits and
the same layout. No entry gets extra fields, a larger card or a featured slot.

| Field | Rule |
|---|---|
| Name, maker | As the maker writes them. |
| Categories | One or more from section 1. |
| Status | Live, Beta, Spec, Pre-launch, Discontinued or Unverified. |
| Inception date | Required. The date the product or spec was first publicly announced or launched, with its source. Marked *(coverage)* when only press gives the date, and *month* or *year* when that is all that is known. Never estimated. Later milestones (GA, paused, retired) are dated too. |
| What it does | At most 60 words. Describes; does not evaluate. |
| How it works | At most 120 words, from primary sources. |
| Links | The maker's site and docs. |
| Sources | Every factual claim links to a source. |
| Last verified | The date someone last checked the entry against its sources. |

**Describe, never rank.** No scores, ratings, "leading", "best", "top" or
comparisons between products. Words a maker uses about itself are quoted and
attributed, never adopted as the site's own voice.

**Fixed ordering.** Within a category, entries are listed alphabetically by
name. A timeline view may instead order them by inception date, which is a
fact, not a judgment (Erik, 2026-10-27: dates visible on every timeline). No
default view is sorted by anything Magnitude controls.

**Magnitude, on the same terms.** Magnitude's entry:

- meets the same criteria, uses the same template and the same word limits;
- cites only public sources, like any other entry, never internal knowledge;
- carries a visible ⓘ beside the maker's name, which says that Magnitude
  publishes the site and is placed by the same rules (Erik, 2026-10-27: a bare
  "Publisher" label meant nothing to a reader);
- is checked against CompliantClick's compliance register (`docs/register.md`)
  before publishing, so it tells readers nothing the product itself may not.

**Relationships.** If Magnitude has a commercial relationship with a listed
company (customer, vendor, partner, investor), that company's entry says so in
one line. The relationship never changes the entry's content, length or
order. The details stay internal (catalog seeds, "Magnitude relationships").

**Disclosure.** Every page footer says the site is published by Magnitude. The
methodology page carries this policy in full.

**Corrections.** Any maker, or any reader, may request a correction. It is made
when it is backed by a source, and every change is logged with its date in a
public changelog. A request without a source is answered, not applied.

---

## 4. Entry checklist

Every entry passes this before it is published, Magnitude's included.

- [ ] Passes the intent test (§2, D7): stated by a person, and it holds when money moves.
- [ ] Fits at least one of the seven categories in section 1.
- [ ] Shipping, public beta or published spec.
- [ ] At least one primary source, linked.
- [ ] Every factual claim has a source.
- [ ] Uses the standard template and stays within its word limits.
- [ ] No evaluative language; any maker claims are quoted and attributed.
- [ ] Inception date set, with its source.
- [ ] Any Magnitude relationship with the maker disclosed in one line.
- [ ] Last-verified date set.
- [ ] Magnitude only: ⓘ present and checked against the compliance register.

---

## 5. Decisions

Accepted by Erik, 2026-10-27, as recommended.

**D1. B2B marketing "intent data" is out of scope.** It is a separate industry
that shares a word, and including it would bury the agent-commerce products the
site is for.

**D2. Makers are told after they are listed, not before.** An entry contains
only public facts. Each maker is notified once its entry is live, with the
corrections path.

**D3. @intent.infra applies this policy; a dispute about the policy itself goes
to Erik.**

---

## 6. Blog

AI agents write the blog. Every rule above applies to posts as well, and these
are added.

**Every post says who wrote it.** The byline names the agent and labels it as
an AI agent. The footer discloses Magnitude as publisher, as on every page.

**Four kinds of post:**

| Kind | What it is | Added rules |
|---|---|---|
| Tool profile | A longer piece on one listed product. | Every listed product gets one, Magnitude's included and no longer than the others. Same sourcing as the catalog entry, and linked to it. |
| Industry news | Something that happened in the space. | Dated. Linked to the primary source (the announcement, filing or release), not only to coverage of it. A later correction is added to the post with its date, never edited in silently. |
| AI advancements | Research or releases that bear on intent and agents. | Cites the paper, release notes or repository. Says what was shown, and doesn't extrapolate past it. |
| Company leaders | A profile of a person leading work in the space. | Public professional record only: role, company, public talks, writing and statements. No personal life, no contact details, no AI-generated images of the person. Quotes only from a public source, linked. The subject can request a correction like any maker. |

**Same rules on news about Magnitude.** A Magnitude story is covered only if
the same story about another company would be. It carries the ⓘ.

**Never invented.** No fabricated quotes, figures, events or images. A claim
that can't be sourced is left out.

**D4. Publishing.** Accepted by Erik, 2026-10-27, as recommended. Tool
profiles, industry news and AI advancements publish as soon as they pass the
§4 checklist. Company-leader profiles wait for a human to review them before
publishing, because an error about a named person costs the most and is the
hardest to take back.

**D5. The intent is the human's, not the agent's.** Erik, 2026-10-27, adding
Visa Flexible Credential to the list: *"intent is not the agent's it's the
humans"*. So a product is in scope when it captures or enforces a person's
intent for their money, whether a person or an agent then acts on it. It does
not have to be built for agents. §1's definition and the payments category
were reworded the same day to match.

**D6. The layer runs from paycheck to checkout.** Erik, 2026-10-27: intent
infrastructure *"occupies a wider timespace, that's upstream of agentic
commerce, between paycheck and checkout."* §1's definition was reworded and the
categories were laid along that timeline. A new category, Allocation, covers
the paycheck end. Six categories became seven. Erik, the same day: *"after the
income lands, it occupies intent infrastructure."* The layer starts when
income lands in an account; earning it and running payroll come before it.

**Neutrality note on D6, for the record.** Magnitude's own product sits at the
paycheck end (per its seed deck), so a definition that includes that end is
favourable to Magnitude. That is acceptable only if the paycheck end is mapped
as thoroughly as checkout: every bank, payroll provider and fintech that
passes the intent test there is listed under the same §2 criteria as Magnitude.
The test is the same at both ends. Magnitude's entry must pass it from public
sources like everyone else's.

**D7. Not so broad that intent is lost.** Erik, 2026-10-27, on D6: *"don't go
so broad that you lose intent."* The paycheck-to-checkout timeline sets where
to look; the intent test in §2 decides what counts. A product is in only if a
person explicitly states what specific money is for or may do, and the
product makes that statement hold when the money moves. Budgets that only
track, savings that only sweep, and rails that move money with no statement
from the person are out, at both ends of the timeline.

**D8. Rails sit in a band underneath, not in the map.** Erik, 2026-10-27,
accepting the intent-map design (roadmap 0.3.5a). Infrastructure that moves
money but carries no person-stated intent (rails such as Bridge and FedNow,
and building blocks such as Web Bot Auth) is shown in a labelled *rails*
band beneath the whole timeline. It must meet §2 criteria 1 to 4, but not the
intent test, and it is never presented as intent infrastructure itself.
The intent test still decides what sits on the map above.

**D9. Four neighbours, all outside.** Erik, 2026-10-27, drawing the map's
frame: intent infrastructure sits between **payroll infra** (left: earning)
and **payment infra** (right: the outcome), and between **mental accounting**
(above: the decision, after Thaler et al.) and **banking infra** (below:
deposits). Each neighbour is outside the category. In one line: *intent
infrastructure is what makes a mental account hold when money moves.* This
places what D7 and D8 left out:
- **Plan-only tools** (budgets beside the account) sit above, as mental
  accounting: the decision recorded but not held.
- **Rails** (FedNow, Bridge, x402) sit below, as banking infra. Agent-identity
  building blocks used at the merchant (Web Bot Auth) sit right, as payment
  infra. D8's "rails band" is this lower neighbour.
Neither is listed as intent infrastructure. Both may be shown on the map as
neighbours, under the same §2 criteria 1 to 4.

**D10. Pre-launch is a status, filtered the same way for everyone.** Erik,
2026-10-27: the public site can have a pre-launch/post-launch toggle across
all entries, *"since more than just magnitude may be in the stealth phase."*
So every view can include or exclude pre-launch entries, and the switch acts on
every company alike. No view hides or shows the publisher alone. A pre-launch
entry still needs a primary source from its maker (§2.2): a public
announcement, page or FAQ. Magnitude's own public site can be that source for
its entry once it describes the product.

**D9 amended (Erik, 2026-10-27).** The map no longer draws mental accounting
above the frame. Three neighbours remain on the map: payroll (left), payment
(right), banking (below). Plan-only tools stay off the map under D7.
