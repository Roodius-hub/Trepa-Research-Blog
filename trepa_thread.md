

Hook

Most prediction markets ask: "Will it happen?"

Trepa asks: "What number will it be?"

That one shift changes everything—incentives, skill ceiling, who wins, and what information markets actually capture.

Here's why precision payouts matter more than you think 🧵

The Core Insight

Traditional markets (Polymarket, Kalshi) are binary: YES or NO, up or down.

You win if you're on the right side. Being 51% confident vs 99% confident pays the same.

Trepa pays based on HOW CLOSE you were. Predict BTC at $97,234, resolve at $97,180? You still get paid proportionally to your accuracy.

Why This Creates Different Incentives

Binary markets reward directional conviction.

Precision markets reward calibrated judgment.

Example:





Binary: "Will BTC be above $100K?" → Bet everything if you think 51%+ chance



Precision: "What will BTC price be?" → Need actual numbers, confidence intervals, risk assessment

The skill ceiling is completely different.

The Mechanics (Keep It Simple)

Trepa runs 1-minute rounds on Solana:





30 seconds to forecast (slider, simple UX)



30 seconds to resolve



1 USDC entry

Winners = everyone below median error Losers = everyone above median error

Prize pool = losing fees, distributed by accuracy weight among winners

It's parimutuel, but for precision.

The 2x2 Matrix Setup

To understand where Trepa fits, I mapped prediction markets on two axes:

Outcome Type: Binary/categorical → Numerical/continuous Liquidity Model: Peer-to-peer markets → Pooled/parimutuel

This reveals four distinct quadrants—and Trepa occupies the one nobody else is in.

[INSERT 2x2 MATRIX VISUAL HERE]

Quadrant Breakdown

Top Left (Binary + Peer-to-peer): Polymarket, Kalshi





Orderbook matching, AMMs



Trade shares, price discovery



Deep liquidity on popular events



Zero liquidity on long-tail

Bottom Left (Binary + Pooled): Traditional sportsbooks, racetracks





Parimutuel betting



Odds shift with pool



Simple yes/no outcomes

Top Right (Numerical + Peer-to-peer): ???





Theoretical: orderbook for continuous outcomes



Extremely complex, liquidity nightmare



Doesn't exist at scale

Bottom Right (Numerical + Pooled): Trepa





Precision + parimutuel hybrid



No counterparty needed



Instant resolution



NEW PRIMITIVE

Strengths of the Precision Model





Partial credit: Near-misses get rewarded, not just binary wins. Lower variance for skilled forecasters.



Information richness: Captures full distribution, not just probability of threshold crossing. Markets reveal "how much" not just "whether."



Skill expression: Can't just pick a side. Need actual numbers. Separates signal from noise faster.



No liquidity fragmentation: Binary markets split liquidity across strike prices. Precision pools everyone into one prediction target.



Speed: 1-minute rounds impossible with orderbook (market maker risk too high). Parimutuel structure enables micro-intervals.

Honest Weaknesses & Trade-offs





Cognitive load: Harder to forecast "97,234" than "above 100K". Barrier to casual users.



Validation of numerical skill: Binary markets have decades of research (Tetlock, Good Judgment Project). Precision scoring at 60-second intervals? We're in new territory. Does median-error threshold actually select for skill at this speed?



Parimutuel opacity: Your payout depends on field accuracy. Can't lock in odds. In binary orderbooks, you know your return before resolution.



Limited event scope: Works for continuous metrics (price, inflation, volume). Doesn't work for categorical events (elections, yes/no). Smaller total addressable market than binary platforms.



Winner pool volatility: If 90% of field clusters around actual outcome, even good forecasters get diluted payouts. Binary markets give you full payout if you're right.

The Arbitrage Question

Can you arbitrage precision vs binary markets?

In theory: Use Trepa precision to calibrate, trade directional on Polymarket/Kalshi.

In practice: 60-second resolution makes this hard. By the time Trepa resolves, binary markets moved.

But: Accumulating Trepa Precision Scores over time could generate alpha signals for longer-horizon binary bets.

Trepa isn't competing with Polymarket—it's a different information layer.

What Trepa Actually Tells Us

Binary markets answer: "What's the probability?"

Precision markets answer: "What's the distribution?"

This matters for:





Volatility measurement (option pricing needs distribution, not just probability)



Tail risk assessment (how wrong could the consensus be?)



Calibration training (you can't hide behind "I said 51%" when you have to say "97,234")

Trepa is a superforecaster training ground that pays you.

The Market Design Contribution

Here's the deeper innovation:

Parimutuel models traditionally worked for categorical outcomes (horse racing).

Trepa proves parimutuel + continuous outcomes + real-time resolution can work.

This is new literature. The median-error threshold, accuracy weighting, 1-minute cadence—these aren't just product choices. They're market design primitives that other builders will reference.

Who This Is Actually For

NOT for:





Casual bettors who want simple yes/no



People allergic to numbers



Long-horizon macro forecasters

MADE for:





Traders who want granular calibration



Quants testing strategies at micro-intervals



Anyone building intuition for numerical ranges



Superforecaster wannabes who need fast feedback loops

You don't just predict. You train.

Open Questions





Does skill persist at 60s intervals? Or is it mostly noise? Need data over hundreds of rounds per user.



Optimal pool size? Too few = high variance payouts. Too many = diluted returns even for skilled forecasters.



Can this scale beyond price? BTC works. But inflation prints, earnings, sports stats—all have different resolution complexity.



What's the Sharpe ratio? For a skilled forecaster putting in 10 rounds/day, what's the risk-adjusted return vs just buying BTC or trading Kalshi?

These are empirical questions. We'll have answers in 6 months.

Prediction Market Evolution

We went from:





Binary orderbooks (Intrade, 2000s)



To AMM primitives (Augur, 2018)



To mobile-first trading (Polymarket, 2024)



To regulatory acceptance (Kalshi CFTC approval, 2024)

Trepa's contribution: Precision + speed + pooled liquidity

It's not replacing binary markets. It's expanding what prediction markets can measure.

The Meta-Take

The beautiful thing about Trepa?

It's not trying to be Polymarket with better UX. It's not Kalshi with crypto rails.

It's asking: "What if we measured accuracy instead of direction?"

That simple inversion creates a new market primitive. Whether it captures $10M or $10B in volume doesn't change the intellectual contribution.

This is what good market design looks like: solve for a different question, don't just optimize the same answer.

Call to Action

Trepa launches early access in May.

If you care about:





Calibration training



Superforecasting



Market design



New Solana primitives

Worth trying for the intellectual exercise alone.

Full docs: https://docs.trepa.io Waitlist: https://www.trepa.app/waitlist

What accuracy-based markets reveal that binary markets miss—that's the real experiment.





