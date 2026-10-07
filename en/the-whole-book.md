# The Options Underwriter

*Henry Zhang*


## Before the First Policy

In 1688 a man named Edward Lloyd kept a coffee house near the Thames, and the merchants who drank there did a strange thing. When a ship was about to sail, its owner wrote the voyage on a slip of paper, and men who had money and nerve wrote their names underneath, each taking a share of the loss if the ship went down, each paid a premium for the risk. They were called underwriters because they wrote under. None of them knew which ship would sink. Every one of them knew, roughly, how many.

That is the whole difference between a gambler and an insurer. The gambler must pick the ship that comes home. The insurer does not pick at all. He prices a fleet, writes many small shares, refuses the voyages he cannot price, keeps money aside for the ones that sink, and is paid for the arithmetic, not for being right.

Most people who trade options are gamblers in the first sense: they buy a contract and need one ship to come home. This book is about the other seat at the table. The option seller writes a policy: he is paid a premium today to cover a move that may never come, in a size he chose, up to a limit he set, for a term that ends on a date printed on the ticket. Every chapter that follows reads one part of an insurance company — the policy, the price, the book, the claims, the reserves, the catastrophe — against a single instrument: the defined-risk credit spread, sold on the index.

This book is education, not advice. It contains no recommendations for you personally, no signals and no promises. Options can lose money faster than stock. A defined-risk spread cannot lose more than its width, but its width can still be more than you can afford, and a run of them can still end an account. Insurers go bankrupt too; the ones that last are the ones that never forgot it. Nothing here is a performance claim; where the text names a number, the number is arithmetic you can check on paper.

Read one chapter a day. Then read them again, in order, because the order is the business: know what you sell, price it, choose what to refuse, build a book instead of a bet, pay claims early, keep reserves, and plan for the year the storm comes.


## Part I: The Policy

An insurance company begins with a piece of paper. Before there is a book, a reserve or a claim, there is one policy: what it covers, what it pays, what it costs, and who is buying it. Get the policy wrong and nothing later in the business can fix it.

The first three chapters are the policy. What an option is when you are the one who writes it, how to know whether the price is fair, and the oldest discipline in the trade: deciding which risks not to write at all.


### 1. The Policy

1. An option is a policy. The buyer pays a premium today to be covered against a move. The seller is the insurer. Everything else in this book follows from knowing which side of the policy you have signed.

2. Every policy has five terms, and the seller must be able to read all five off the ticket before signing.

3. The premium is what the buyer pays you now. It is yours from the moment the order fills, and it is the only income the business will ever have.

4. The strike is the attachment point: the level at which the policy starts to pay. Everything between the price today and the strike is the deductible the buyer carries himself.

5. The width of the spread is the limit: the most the policy can ever pay. A policy without a limit is not a policy. It is a promise to pay whatever the world decides.

6. The expiry is the term. When the term ends without a claim, the premium is earned and the policy is gone. Most policies expire this way; that is why the business exists.

7. The size is the number of policies written. It is the only term the market cannot set for you, and the one most often written in panic or greed.

8. The buyer is not a fool. He pays to sleep at night, to protect a portfolio, to hedge a book bigger than yours. Do not despise the customer; price him.

9. You do not need to know where the market will go. An insurer does not know which house will burn. He needs to know how often houses burn, and to be paid more than that.

10. A trader asks: will this go up? An underwriter asks: what is this risk, what is it worth, and can I pay the claim if it comes?

11. Write only cover you can pay. The policy you cannot honour is the one that will be called.

12. The sentence before every sale: *I am paid one to cover four; the limit is the width; the term ends Friday; I can pay the full claim.* If the sentence cannot be said, the policy cannot be written.

13. The gambler needs to be right once. The insurer needs to be paid fairly a thousand times and solvent on the day he is wrong.

## Commentary

The first chapter is a change of seat, and the seat changes everything. Most people meet options as buyers: a cheap contract, a big possible payout, a bet on direction. From the buyer's side every option is a lottery ticket, and the only question is which ticket wins. From the seller's side the same contract is a policy, and the question is not which ticket wins but whether the premiums, across all the tickets written, are larger than the claims.

The five terms are the policy's anatomy, and each maps onto a piece of the credit spread. The credit received is the premium. The short strike is the attachment point; the distance from the price to it is the deductible the market must cover before you pay anything. The long wing is the limit; the spread's width is the largest claim you can ever face. The expiry is the term. And the size is the one term you set entirely by yourself, which is why the next twelve chapters keep returning to it.

The sentence in rule twelve is the policy read aloud. A five-wide spread sold for one pays one and can lose four; the four must already be money you can lose without closing the company. An insurer who writes cover he cannot honour is not taking more risk than his rivals. He is in a different business altogether, one that ends the first time the storm arrives.


### 2. The Price of Fear

1. A policy has two prices: the premium the buyer pays, and the loss cost, which is what the policy will pay out on average. The business lives in the gap between them.

2. The premium is the market's fear. In an option, it is called implied volatility: the size of the move the buyers are willing to pay to be covered against.

3. The loss cost is the market's truth. In an option, it is the move that actually happens: realised volatility, measured after the fact, day by day.

4. When fear is larger than truth, the underwriter is paid for writing. When truth is larger than fear, every policy written is a gift to the buyer.

5. Fear is usually larger than truth, because people pay more to sleep than the storm will cost them. That is not a law of nature. It is a habit of buyers, and habits break.

6. Never price a policy from the premium alone. A rich premium on a risk that is about to happen is not rich. It is accurate.

7. Keep your own table. An insurer prices from its own claims history, not from the salesman's brochure. Your table is a record of how far the index actually travelled over the terms you write.

8. From the table, ask one question before every sale: over this term, how often has the market reached my strike, and what did it cost when it did?

9. If one week in ten the market reached the strike and the average claim was three, the loss cost is three tenths. A premium of three tenths is a policy written for nothing. A premium of a half is a business.

10. Price the term you sell, not the term you remember. A month of calm makes every policy look overpaid; the claim does not care what last month was like.

11. The cheapest policy is the one you were paid least to write. When premium is thin, the right size is small, and the right number is often none.

12. Do not cut the price to win the business. The market will always sell you more volume at a worse price, and there is no buyer whose order is worth writing at a loss.

13. The underwriter's edge is not knowing the future. It is knowing what the future usually costs, and refusing to sell it for less.

## Commentary

Every insurer in history has been in the same business: collect slightly more in premium than will be paid out in claims, across enough policies for the difference to become reliable. The option seller's version has a name — the gap between implied and realised volatility — and a well-documented tendency: over long stretches, buyers have paid more for index protection than the moves they were protected against turned out to cost. That tendency is the margin the underwriter collects. It is not guaranteed, and it is thinnest exactly when the market feels calmest.

Rule nine is the actuarial calculation in its simplest form. Suppose, over the term you write, the index reached your strike one time in ten, and when it did, the average loss on the spread was three. Then each policy costs, on average, three tenths in claims: one tenth of the time, three. Sell it for three tenths and you have built a machine that does nothing but pay your commissions. Sell it for five tenths and the expected margin is two tenths per policy, before costs — the whole business, in one line of arithmetic you can redo with your own numbers.

The danger is that the table is made of the past. A calm month makes every premium look generous, and an underwriter who prices from the last month alone will be writing his cheapest policies just before the most expensive claims. The cure is a long table, an honest one, and a willingness to write nothing when the premium is too thin to cover what the table says the storms cost.


### 3. Underwriting

1. Underwriting is the art of saying no. A company that writes every policy offered to it is not an insurer. It is a target.

2. Before every sale, the underwriter looks at the risk, not the premium. The premium will always look attractive; that is how the bad risks are sold.

3. Some hazards are printed on the calendar. The rate decision, the inflation report, the earnings call, the election night. Writing cover across them is writing fire insurance on a house whose owner has already bought matches.

4. A known hazard must be excluded, priced higher, or written smaller. It must never be written at the ordinary rate.

5. Ask who is buying, and why now. When the market is suddenly eager to buy the exact cover you are selling, at the exact strike, the eagerness is information.

6. The worst buyer is the one who knows more than you. In insurance this is called adverse selection: the people most keen to buy fire cover are the ones who smell smoke.

7. Some ground is not insurable at any price. A market falling in a straight line, a volatility index rising day after day, a gap that has not been filled: the experienced underwriter closes the book and waits.

8. Declining a policy costs nothing but the premium you did not collect. Writing a bad one can cost the company.

9. Write in the hours the risk is clear. The open is the ground of confusion; the first hour's moves are often the ones that change their mind.

10. Read the policy in full before signing. The strike, the width, the term, the size, the events inside the term. A clause you did not read is a clause written against you.

11. An insurer is bound by utmost good faith, and so is the trader who insures: no lying to yourself about why this policy is different.

12. The book of declined policies is as valuable as the book of written ones. Keep it, and read it after the storm.

13. A company is made by the business it refuses.

## Commentary

Insurance law has a phrase for the duty both sides owe each other — *uberrimae fidei*, utmost good faith — because the business only works if the risk written is the risk described. In the market there is no counterparty to describe the risk honestly to you. The calendar does it instead. A rate decision, an inflation print or an earnings report inside the term of your policy is a known hazard, and an underwriter who writes across it at the ordinary premium is not taking a calculated risk. He is ignoring the form.

Adverse selection is the subtler danger. In a normal market, the people buying index protection are hedgers: pension funds, dealers, long-only managers paying for sleep. Their buying is the reason premiums run rich. But when demand for cover suddenly concentrates — everyone wants the same puts, at the same strikes, at once — the buyers are no longer paying for sleep. They know, or fear, something specific. A seller who fills that demand at yesterday's price is the insurer who wrote fire cover for the man who smelled smoke.

The declined book in rule twelve is the cheapest education in the business. Every day you do not write, note what you would have written and why you refused. After a storm, read it. Most of the time you will find you gave up a little premium; once in a while you will find you declined the policy that would have been the year's worst claim. That second entry is the one that teaches a company to keep saying no.


## Part II: The Book

One policy is a bet. A thousand policies, priced well and spread wide, are a business. The difference is not cleverness; it is arithmetic that only works when the pieces are many, small and not all on the same street.

Chapters four to six are about the book: why size matters more than any single forecast, why a hundred policies on one coast are one policy, and why every policy must have a limit written on it before it is sold.


### 4. The Law of Large Numbers

1. One policy is a bet. Many policies, each small, are a business. The law of large numbers works only for those who obey both halves of the sentence.

2. The insurer does not know whether this house will burn. He knows that out of ten thousand houses, a certain number will. His profit is the average, and the average only appears in large numbers.

3. A seller who writes one large policy a month is not running a book. He is running a coin, and calling it a company.

4. Size each policy so that the worst claim it can make is a bad week, never a closed company.

5. The limit of the spread, times the number written, is the most the book can lose on one policy. Know this number before the order, not after.

6. Size before frequency. Trading more often does not make a book safer; writing each policy smaller does.

7. The averages are slow. A run of five claims in a row is not proof that the pricing is wrong, and a run of twenty quiet weeks is not proof that it is right.

8. Do not raise the size after a good month. The quiet month did not make the storm smaller; it only made you forget it.

9. Do not raise the size after a bad month to win it back. That is not underwriting. That is the gambler's chair, entered through the back door.

10. The number of policies written in a year is the sample. A business with a small sample does not have a margin. It has a story.

11. Each policy must be written as though it were the hundredth of the same kind, because it is. The decision is not this trade; it is the rule that produced it.

12. The insurer's patience is arithmetic: when the margin is real and the size is small, time does the work.

13. Many small, each survivable, all priced: that is the whole law.

## Commentary

The law of large numbers is the reason insurance exists at all. One house is an unpredictable thing; ten thousand houses are a statistic. The insurer's margin is invisible on any single policy and reliable across the book — but only if the book is large and the policies are small. Remove either condition and the law stops working. A seller who writes one big spread a month has a sample of twelve a year: too few for any margin to show itself through the noise, and too large each for a single bad month to be survivable.

Rule five is the arithmetic every underwriter does before writing. A five-wide spread sold for one has a limit of four per contract. Ten contracts is a limit of forty per policy, before the premium. If forty is a bad week for the account, the size is right. If forty is the account's whole quarter, the size is a bet, whatever the probability on the screen says. The probability tells you how often the claim will come; only the size tells you what it will cost when it does.

The two temptations in rules eight and nine are the same mistake facing in opposite directions. After a quiet run the margin looks permanent and the size creeps up; after a claim the loss looks like a debt that a bigger policy could repay. In both cases the size is being set by the last result instead of by the rule. An insurer that changed its pricing every time a house burned or failed to burn would not be an insurer for long.


### 5. Accumulation

1. A hundred policies on the same coast are one policy. The hurricane does not visit them one at a time.

2. The insurer's second enemy, after the bad price, is accumulation: many risks that look separate and are in fact the same risk wearing different names.

3. Puts sold on the index, on the technology fund, on the five largest companies in the index: three names, one coast.

4. On a quiet day the policies move separately. On the day of the storm they all move together. Correlation is a fair-weather word.

5. Add up the book by coast, not by ticket. How much does the whole book pay if the market falls five percent before the term ends? That number is the real size.

6. Set a limit per coast and keep it. An insurer that caps any one house but not any one county has capped nothing.

7. Time is a coast too. Ten policies all expiring on the same day are one claim waiting for one bad afternoon.

8. Spread the terms. Policies that end on different days give the book more than one chance to be right and one storm fewer to be wrong.

9. Both sides of the same index are not diversification. A put spread and a call spread sold together cover two coasts that cannot both be hit by the same move — that is a different and useful thing — but both are still written on one sea.

10. When everything you own falls together, you did not own many things. You owned one thing many times.

11. The accumulation that ruins a company is always the one nobody added up, because each policy, alone, looked small.

12. Before adding a policy, ask: what else in the book pays out on the same day, for the same reason?

13. Count the coasts, not the houses.

## Commentary

Insurers learned accumulation the expensive way. A company could write thousands of home policies, each one modest, and discover after a single hurricane that most of them had been written within forty miles of the same shoreline. Every policy passed the individual size check; the book as a whole had written one enormous policy on one storm. Modern insurers now map their exposure by zone precisely because each policy, inspected alone, never shows the danger.

The option seller's coasts are less visible but just as real. A put spread on the index, another on the technology fund and a third on a large technology stock look like three positions. On an ordinary day they even behave like three: one drifts, one rallies, one holds. On the day the market falls hard, they converge, because they were always the same exposure to the same fear. Rule five replaces the count of tickets with a single question — what does the whole book lose if the market falls five percent this week — and that answer, not the number of positions, is the book's true size.

Rule nine is a nuance worth keeping. A put spread and a call spread sold on the same index together form an iron condor, and they are genuinely not the same coast: no single move can reach both short strikes at once. That is a real reduction in risk. But they still share one sea — one index, one volatility, one session — so the condor is better understood as one policy with two sides than as two independent policies. Counting it as two is how a book that believes it is diversified turns out to be concentrated.


### 6. Limits and Deductibles

1. Every policy must carry a limit, written on its face before it is sold. The limit is the line between a business and a disaster.

2. In a credit spread, the limit is the long wing. The width between the strikes, less the premium, is the most the policy can ever cost.

3. Selling an option without the wing is writing cover without a limit. Most days it looks the same and earns a little more. On one day it is the end of the company.

4. The extra premium earned by dropping the wing is the price of unlimited liability. No premium is large enough to pay that price.

5. The deductible is the distance from the price to the strike. The buyer pays everything inside it himself. Choose it with care: a small deductible pays well and is claimed often; a large one pays little and is claimed rarely.

6. Neither deductible is better. Each is a different policy, with a different premium and a different claim rate. The mistake is to forget which one you wrote.

7. A narrow spread has a small limit and needs many to matter. A wide spread has a large limit and needs few. The book's limit is the width times the size, and only that number counts.

8. The limit protects the company from the world. It does not protect the company from its own size. A limited policy, written too many times, is an unlimited book.

9. Never remove the wing to save its cost. The wing is the cheapest part of the policy, and it is the only part that is never wrong.

10. When the short leg is closed in a claim, the wing may be kept. It costs little, it may still pay, and it guards the account until the term ends.

11. Read the limit aloud before every sale: *the worst this can cost is the width less the credit, times the size.*

12. An underwriter can be wrong about the weather. He must never be wrong about the limit.

13. Know the worst, and write it down, before you collect the best.

## Commentary

Unlimited liability is the one policy no sane insurer writes, and selling an option naked is exactly that policy. Most days a naked short option behaves like a spread with a little more income, because the storm that would reach far beyond the strike does not come. The extra income is the market paying you to remove the limit. It is never enough, because the event it insures against is the one that ends companies, and an insurer is not paid for most days. It is paid for surviving the one day that matters.

The deductible in rule five is where the trader's real choice sits. A strike close to the price is a policy with a small deductible: it is claimed often and it pays a large premium for that reason. A strike far away is a large deductible: claimed rarely, paid little. Both are legitimate products with different claim rates. The error is mixing the two in your head — writing the near strike for its premium and then being surprised by the claims, or writing the far strike and sizing it as if it could never be claimed.

Rule ten is the one place where the limit stays useful after the claim. When the short leg is bought back to settle a tested position, the long wing is often worth very little; selling it saves almost nothing and gives up its protection. Kept until the term ends, it costs nothing more and remains the limit on whatever the account does next. The habit is simple: cut the short leg, keep the wing.


## Part III: Claims and Capital

Premium is collected in fine weather. An insurer is judged in the season of claims: how quickly it pays, how much it kept aside, and whether, when the year is added up, it earned more than it paid out.

Chapters seven to nine are claims and capital: settling a tested position at a known cost instead of arguing with the market, the reserve that lets you keep writing when others cannot, and the one ratio that says whether you are running a business or a charity.


### 7. Claims

1. A claim is not a failure. It is the reason the premium was paid. An insurer who is outraged by claims is in the wrong business.

2. The claim begins when the market approaches the attachment point. The underwriter's whole skill is in what he does in the hour before the policy pays in full.

3. Decide the settlement before the sale: at what price the short leg is closed, and how much the claim is allowed to cost. A claim settled by rule is a cost. A claim settled by hope is a lawsuit with the market.

4. Settle small and early. The cheapest claim is the one paid while it is still small.

5. Do not argue with the claim. The market does not read your reasons, and the delay it charges for arguing is always larger than the claim.

6. When one side of the book is hurt and the other is far away, the second side may be written against the first: an iron condor built in the moment of injury. This is an adjustment, not a new opinion.

7. Hedge only when hurt. A condor sold at the start pays for two coasts on every policy; a condor built when one side is tested is paid for by the side that is already working.

8. Never add size to the side that is losing. Writing more cover on the house that is already burning is not averaging down. It is a second fire.

9. Close the short leg; keep the wing. The short leg is the liability. The wing is the reinsurance, and it may still pay.

10. A claim paid on the rule is a good day for the business, even when it is a bad day for the account. The rule is the company. The account is one season.

11. After every claim, write it in the ledger: what triggered it, what it cost, whether the rule was followed. The ledger does not judge the market. It judges the underwriter.

12. Do not write the next policy to make back the last claim. The next policy has its own price, and the last claim is already paid.

13. Pay claims promptly, honestly and by rule, and the company survives its worst year.

## Commentary

Insurers that fail usually fail in claims handling before they fail in capital. Delaying, disputing and hoping a claim goes away feels cheaper in the moment and is always more expensive in the end. The option seller's version is the tested spread that is held past its stop because the market *should* turn: the argument is with a counterparty that does not listen, and the cost of losing the argument grows with every point the price travels into the policy.

Rule six describes the one adjustment that is a legitimate part of claims handling rather than a new bet. When a put spread is tested because the market is falling, the call side of the same index is usually far away and cheap to write. Selling a call spread against the hurt position turns it into an iron condor: the new premium reduces the cost of the claim, and no single move can reach both short strikes. It is written because one side is already in claim — not as a standing habit — which is why the rule is to hedge into the condor only when hurt.

Rule twelve guards the door the gambler comes back through. After a claim, the next policy wants to be larger, or nearer, or written on a hunch, so that the account can be made whole by Friday. That policy is no longer priced by the table in chapter two. It is priced by the loss, and a company whose prices are set by its last claim has stopped underwriting and started chasing.


### 8. Reserves

1. Reserves are the money an insurer keeps for the claims it has not yet received. A company without reserves is solvent only until the first bad week.

2. The reserve is not idle money. It is the part of the capital that makes the rest of the capital usable.

3. Never write premium against the whole account. The broker will allow it; the broker is not the one who closes your company.

4. Keep a fixed share of the account unused by any policy, every day, in every market. The share is set in the quiet and kept in the storm.

5. The reserve must be large enough to pay the worst claim in the book, and the one after it, and still leave the company able to write the next policy.

6. The reserve is what lets an insurer write in the hard market. After the storm, premiums rise and buyers are many; only the company with money left can sell them cover.

7. A seller who is fully invested in calm weather has nothing to write with when the prices become good.

8. Do not borrow from the reserve to write one more policy. That policy will always look like the best one of the month. That is the reason it must not be written.

9. Margin requirements are the regulator's minimum, not the underwriter's standard. A company that holds only what the regulator demands is one bad day from the regulator.

10. When a claim is paid, refill the reserve before writing again. A company that writes with a reserve already spent is writing with money it does not have.

11. The reserve is measured in losses, not in dollars: how many full claims can the account pay before it stops?

12. The size of the reserve is the size of the company's patience.

13. Premium is what the business earns. The reserve is what lets it keep earning.

## Commentary

Reserving is the least glamorous part of insurance and the one that decides which companies survive. Premiums arrive in good years and claims arrive in clusters; the reserve is the bridge between them. A company that spends its premium as it comes in — or worse, writes more business against it — has no bridge. Its first cluster of claims is also its last.

For the option seller, the reserve is unused buying power. The broker will let you sell spreads until the account's capital is fully committed, and on most days that would make more money. Rule four sets a fixed share aside instead — decided in calm conditions, when it is easy, and kept in rough ones, when it is hard. Rule eleven measures it in a way that cannot be talked around: if the largest policy can lose forty, and the reserve is two hundred, the company can pay five full claims before it is out of business. That number is the account's real distance from ruin.

The hard market in rule six is the reserve's reward. After a crash, premiums rise sharply, buyers are desperate for cover, and policies written at those prices have the widest margins the business ever sees. The sellers who wrote with every dollar in the calm are busy paying claims and cannot take part. The company that kept its reserve is the only one left with something to sell, and the hard market is when it earns back the patience it paid for in the soft one.


### 9. The Combined Ratio

1. An insurance company is judged by one number: the combined ratio. Claims paid plus the costs of doing business, divided by the premium earned.

2. Below one hundred, the company made money underwriting. Above one hundred, it paid its customers to be its customers.

3. The underwriter's costs are many and small: the commission on every fill, the spread between bid and ask, the slippage on a stop in a fast market. Each is a cent. Together they are often the whole margin.

4. Count the costs per policy, not per month. A policy that earns a dime and costs four cents to write and close is a six-cent policy, not a ten-cent one.

5. The cheapest cost to cut is the trade not made. Every adjustment, every early close, every reopened position pays the toll again.

6. Do not chase volume. A company paid by premium written grows fat in the soft market and dies in the hard one. A company paid by combined ratio writes less and lasts.

7. Keep the ratio monthly, from the ledger, not from the account balance. The balance mixes luck with skill. The ratio separates premium from claims and claims from costs.

8. A ratio above one hundred is not a reason to write more. It is a reason to stop and find out which line is wrong: the price, the size, the selection or the claims.

9. A ratio below one hundred in a quiet month proves very little. The storm has not been counted yet. Judge the ratio over a year that includes bad weather.

10. If one kind of policy carries the whole book's losses, stop writing that kind. Insurers drop lines of business every year; traders rarely drop a setup. The insurers are right.

11. The ratio is the company's honesty. It does not care how good the story behind the policy was.

12. A business that cannot say its combined ratio does not know whether it is a business.

13. Earn the premium, pay the claims, count the costs, and let the number speak.

## Commentary

The combined ratio is the simplest honest summary an insurer has, and it translates directly. Take the premium collected on every spread over a month. Take the cost of every claim — the losses on positions that were tested and closed. Add every cost of trading: commissions, the bid-ask spread paid on entry and exit, the slippage of stops filled in fast markets. Divide claims plus costs by premium. If a month collected one thousand in premium, paid seven hundred in claims and one hundred and twenty in costs, the ratio is eighty-two: eighteen of every hundred collected stayed in the business.

Rule three is where most option sellers quietly lose. A spread that collects a small credit and is opened, adjusted and closed several times can pay most of its premium away in tolls before the market has done anything at all. The costs never appear as a single large loss, so they are rarely noticed; the ratio is the only place they become visible. The cheapest improvement most books can make is not a better forecast but fewer round trips.

Rule ten borrows the insurer's bluntest habit. When one line of business — homes on one coast, cars in one city — produces losses year after year, the company does not argue that the next year will be different. It stops writing that line. A trader who finds that every loss in the ledger comes from the same setup, the same time of day or the same event week has learned something an insurer would act on at once: drop the line.


## Part IV: Catastrophe and the Long Run

The history of insurance is written in catastrophe years. Companies that were profitable for a decade disappeared in a week, not because they priced the ordinary days badly but because they never imagined the extraordinary one.

The last four chapters are about the long run: the storm that markets call a hundred-year event and deliver every few years, the insurance an insurer buys for itself, the patience of money held before it is earned, and the discipline that lets a company outlive its founders.


### 10. Catastrophe

1. Insurers do not go broke on ordinary claims. They go broke on catastrophes: the one event that sends every claim in the book at once.

2. The market calls these events rare. It has delivered one every few years. The underwriter who prices them as rare is pricing his own disappearance.

3. On one Monday in October 1987 the index fell by a fifth in a single session. In February 2018 the market's fear gauge more than doubled in one day, and products built on its calm were closed for good. In March 2020 the index lost a third of its value in about a month.

4. A catastrophe is not a large ordinary day. It is a different kind of day: the gaps skip the stops, the quotes widen, the exits close, and every coast is hit together.

5. Run the storm in advance. Ask: if the index gaps five percent overnight, what does the book owe in the morning? If it falls ten percent in a week? Write the answers down while the sun is shining.

6. The book is fit to write only if it survives the storm on paper. If the paper storm closes the company, the size is wrong today, not on the day it comes.

7. Defined risk is what makes the storm countable. The limit on every policy turns the catastrophe from an unknown into a sum.

8. A stop is a plan for an ordinary day. In a catastrophe the market can open beyond it. Only the wing is guaranteed to be where you left it.

9. The worst storms come after the longest calm, because the calm is when everyone writes the most cover at the thinnest premium.

10. After a catastrophe, do not retire. The hard market that follows pays the highest premiums the business will ever see, to the companies that still have capital.

11. Do not try to predict the catastrophe. Its date is unknowable. Its existence is certain.

12. The question is not whether the storm will come. It is whether, on the morning after, the company will still be open.

13. Price the ordinary day. Survive the extraordinary one.

## Commentary

When Hurricane Andrew struck Florida in 1992, the losses left several insurers insolvent. Most of them had priced their ordinary policies reasonably well. What they had not done was add up what the whole book would owe if one storm hit the whole coast in one night. The lesson that the surviving industry took was not to forecast hurricanes better. It was to model the catastrophe in advance, on paper, and to refuse any size the paper storm could not survive.

The option seller's catastrophes are part of the public record, and they arrive more often than the word *rare* suggests. The index fell about a fifth in one session in October 1987. On 5 February 2018 the volatility index more than doubled in a single day, and exchange-traded products that had been short volatility were wound down. In February and March 2020 the index fell roughly a third in a few weeks. In each case, sellers who had sized to ordinary days met a day that was not ordinary, and the claims arrived together, at the open, through the stops.

Rule eight is why this book insists on the defined-risk spread. A stop-loss is an instruction for a market that trades continuously; in a gap, the market opens past it and the fill comes wherever liquidity returns. The long wing is not an instruction but a contract, and it is the one protection that is where you left it on the morning after. Its premium is the cost of making the catastrophe a number rather than a surprise.


### 11. Reinsurance

1. Every serious insurer buys insurance for itself. It is called reinsurance, and it is the reason the company is still writing after the storm.

2. Reinsurance costs a share of the premium. That share is not a loss of profit; it is the price of being allowed to stay in business.

3. In a credit spread, the long wing is reinsurance bought at the moment the policy is written: part of the premium is handed on, and the largest claim is capped.

4. A wing far away is cheap reinsurance with a high attachment point. A wing near the short strike is expensive reinsurance that caps the claim sooner. Choose the cover you can afford, not the cover that looks cheapest.

5. When a short option has fallen to a few cents, buy it back. The few cents are the cheapest reinsurance in the market: they close a policy that can still be claimed for its full limit.

6. Do not hold a nearly-expired policy to collect the last penny. The last penny is paid for by the whole limit.

7. A small, permanent tail cover for the whole book — a little protection far below the market — is the insurer's catastrophe treaty. It loses money most years. It is meant to.

8. Reinsurance bought after the storm is expensive. Reinsurance bought in the calm is cheap. The time to buy it is the time it feels least necessary.

9. Do not let the reinsurance become a bet. Cover that is larger than the book it protects is a new position, and it must be underwritten as one.

10. The insurer that refuses to pay for its own cover keeps a little more premium every year, and gives all of it back in one.

11. Cede enough to sleep, and keep enough to earn.

12. The cost of reinsurance appears in the combined ratio every month. Its value appears once in ten years. Judge it on the ten years.

13. An insurer insures others. A company that lasts also insures itself.

## Commentary

Reinsurance is how an insurer turns an unbounded book into a bounded one. A primary insurer writes thousands of policies, then cedes a slice of the premium to a reinsurer who agrees to pay the claims above some level. The primary keeps less of the premium in a good year and is still open in a bad one. No large insurer operates without it, and none of them regards its cost as wasted.

The option seller already buys reinsurance on every policy: the long wing of the spread is cover purchased with part of the credit. Rule four is the trade-off a reinsurance buyer faces. A wing placed far from the short strike is cheap, because it attaches only after a large move; it leaves a large claim possible, but caps it. A wing placed close is expensive and caps the claim early. Neither is correct in general. The right choice is the cover that keeps the worst claim inside the reserve from chapter eight.

Rule five is the reinsurance most sellers skip. A short option that has decayed to a few cents still carries the full liability of the policy until it expires. Buying it back for those cents closes the liability; holding it to earn them keeps the whole limit at risk for almost no reward. Insurers cancel policies whose remaining premium no longer pays for their remaining risk, and the habit costs pennies to copy.


### 12. Float

1. The insurer is paid first and pays claims later. The money held in between is called float, and it is the oldest advantage in the business.

2. When a spread is sold, the credit arrives in the account that morning. It is not yet profit. It is premium the company holds in trust for a policy that has not ended.

3. Premium is earned as the term passes. The decay of an option is the insurer's earning, hour by hour, of money it already holds.

4. Do not count unearned premium as income. A company that spends its premium before the term ends has spent money that belongs to its claims.

5. Do not size the next policy on credit that has not been earned. Float is not capital.

6. Time is the only part of the policy that always runs in the insurer's favour. Every day a policy is open and unclaimed, more of its premium is earned.

7. Do not fight the term. A policy closed early to lock in half the premium also gives up the rest of the earning; close early only for a reason the rules name.

8. The last days of a term earn the most premium and carry the sharpest claims. Near the end, a policy is all reward or all claim within hours. Decide in advance which policies are held to the end, and which are closed before it.

9. The buyer is paying for time as much as for cover. The longer the term, the more premium, and the more weather the policy must survive.

10. Float is valuable only if its cost is low. A book whose claims eat all its premium has float that costs more than borrowing.

11. Patience is the insurer's working capital. The company that can wait for its premium to be earned does not need to forecast the market at all.

12. The trader wants to be paid by the move. The underwriter is paid by the clock.

13. Hold the premium in trust, earn it by the day, and let time keep its promise.

## Commentary

Float is the reason great insurers have also been great investors: they hold large sums of other people's premium for long stretches before the claims come due. The option seller's float is small and short — the credit from a spread held for days or weeks — but the principle is the same, and so is the trap. The credit sitting in the account looks like profit. Until the policy expires, it is a liability with a balance attached.

Rule three describes how insurers recognise income: premium is earned in proportion to the time that has passed in the policy's term. An option does the same thing through time decay. A spread sold for one with ten days to expiry has not made one on the first day; it has made whatever the clock has released, and the rest is still held in trust against a claim. Treating the full credit as earned is how a book ends up sizing new policies on money it may need to give back.

Rule eight is the clock's warning. Time decay accelerates near expiry, so the final days of a policy release the most premium — and price moves near the strike swing the claim hardest at the same moment. Insurers who write short-term cover know exactly which policies they let run to the end and which they close before the final hours. The option seller needs the same rule written down, because in the last afternoon of a term there is no time left to decide it.


### 13. The Hundred-Year Company

1. The aim is not a good year. It is a company that is still writing policies in twenty years.

2. Insurance moves in cycles. In the soft market, premiums are thin and everyone writes. In the hard market, after the storm, premiums are rich and few can write.

3. In the soft market, write less. Thin premium is not an opportunity; it is the cheapest the risk will ever be sold, which is the reason not to sell much of it.

4. In the hard market, write carefully, at good prices, with the reserve the soft market taught you to keep.

5. The company that grows fastest in the soft market is the one that fails first in the hard one.

6. Keep the rules in writing: the size, the limit, the coasts, the reserve, the claim rule, the events excluded. Rules held in memory change with the mood. Rules written down change only by decision.

7. The ledger is the company's actuary. Every policy written, every claim paid, every cost, every policy declined. A company without a ledger has opinions instead of numbers.

8. Review the ledger on a schedule, not after a loss. A review after a loss is an argument. A review on the calendar is underwriting.

9. Change a rule only with evidence from the ledger, and never on the day it was broken.

10. The company does not need to be clever. It needs to be priced, limited, diversified, reserved and patient, every day, including the days that are boring.

11. Most of the work is declining business. Most of the profit is premium on policies that were never claimed. Most of the survival is the size of the ones that were.

12. A trader is measured by his best trade. An insurer is measured by its worst year, and by whether it was still open the year after.

13. Write the policy, price it, limit it, spread it, reserve for it, pay its claims, earn its premium — and do it again tomorrow, for twenty years.

## Commentary

The oldest insurance houses are centuries old, and none of them lasted by being right about the weather. They lasted by writing business they could price, refusing business they could not, keeping reserves through good years, and paying claims through bad ones. The cycle in rules two to five is the industry's own description of itself: long soft stretches in which premium is cheap and competition is fierce, broken by catastrophe years after which prices rise and capacity is scarce. The companies that survive the cycle are the ones that grew slowly in the soft years.

For the option seller, the soft market is the long calm in which volatility is low and spreads pay little. It is precisely when writing more feels safest, and the first ten chapters of this book have explained why it is not. The hard market is the aftermath of a storm, when premiums are rich and many sellers are no longer able to write. A book that kept its reserve and its limits through the calm arrives at the hard market with something to sell.

Rules six to nine are the company's governance, and they are the part an individual trader most often skips. Writing the rules down, keeping a full ledger, and reviewing it on a calendar rather than in the heat of a loss are what turn a trader's habits into a company's policy. None of it predicts the market. All of it is what lets the business keep doing what this book began with: being paid to cover a risk, a thousand times, and still being open on the day it is wrong.
