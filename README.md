NutriMatch | Product Management Case Study

Product: Personalized food scanner and nutrition decision support
Role: Founder & Product Lead (independent project, built solo with AI development tools)
Timeline: January 2026 – present
Stage: Functional MVP in early user testing
Focus: Consumer health tech, product discovery, UX, data quality and product validation

1. Why I Built NutriMatch

I work in quality at a chocolate manufacturer, and I often scan food with Yuka, a popular food-scanning app. When I mentioned it to colleagues, none of them had heard of it. Using it more closely, I noticed two problems.

The alternatives didn't fit where I live. In my experience with the free version, the healthier alternatives it suggested were often products I couldn't find in Canada. Someone in Nigeria, China or anywhere else faces the same problem. People need good options they can actually buy in their own country.

"Good" or "bad" isn't how people eat. Most popular chocolate bars score poorly, and they are not health food. But people still want a Snickers or a Cadbury bar some days. Healthier products are also often more expensive, so telling people to avoid everything "bad" isn't realistic.

My idea: instead of judging food, help people fit it into their own goals. If you're trying to lose weight, NutriMatch should explain how a product fits that goal, and how a smaller portion could still work, rather than simply telling you not to eat it.

2. The Problem

Food labels contain plenty of information, but most people find it hard to interpret, and a product that suits one person may not suit another.

Existing scanners tend to give one universal score. That score doesn't reflect the user's goals, and it can feel judgmental about the foods people enjoy.

Product opportunity: a simple, personalized tool that turns complex nutrition data into plain-language guidance based on each person's goals.

3. Target Users
Everyday shoppers who want to eat better but don't have a nutrition background.
People working towards a specific goal: weight management, more protein or fibre, or less added sugar or sodium.
People who want guidance on fitting treats into their goals, not a list of foods to avoid.
4. My Role

I led NutriMatch end to end as an independent project, building it solo by writing and refining prompts in Lovable. My work included:

Defining the problem, target users and product vision.
Turning user needs into requirements and acceptance criteria.
Prioritizing features and scoping the MVP.
Designing the user experience and recommendation logic.
Integrating Open Food Facts data.
Defining data validation rules and testing the product.
Gathering early user feedback and iterating on it.
5. MVP Features
Barcode scanning and search: scan or search packaged foods to see their nutrition information.
Personal goals: choose 1–3 goals, such as weight management, more protein or fibre, or less added sugar or sodium.
Goal-fit guidance: a plain-language explanation of how a product fits each selected goal.
Portion comparison: see how a half portion changes the picture, so a treat is explained rather than simply discouraged.
"How calculated": an expandable explanation of how each result is worked out.
Mobile-first design: compact screens and simple language.
6. Key Product Decisions
Personalization instead of a universal score

Decision: score products against each user's goals rather than give every product one health score.
Why: whether a food is suitable depends on the person and what they're trying to achieve.

Explain, don't judge

Decision: show how a product, or a smaller portion of it, can fit a goal instead of labelling it "bad."
Why: people will keep eating the foods they enjoy, and guidance they can live with is more useful than guidance they will ignore.

Explore before sign-in

Decision: let users scan and see results without an account; ask them to sign in only to save products or preferences.
Why: people should see the value before being asked to commit.

Data quality before recommendations

Decision: validate nutrition data before scoring, and show "Unavailable" instead of a score when data is missing or contradictory.
Why: a confident recommendation built on bad data destroys trust. Checks include energy-value (kcal/kJ) consistency, serving-size validation, macronutrient plausibility and added-sugar ingredient cross-checks.

7. Testing and Validation

NutriMatch uses Open Food Facts, an open food database with inconsistent data quality, so testing focused on reliability:

57 passing tests covering scoring accuracy, missing-data handling, nutrient consistency and kcal/kJ checks.
Issues found and fixed: barcode scanning failures, inconsistent energy values, ingredient-data conflicts and incorrect product identification.
8. Early User Feedback

More than 10 people tried NutriMatch during early testing. Their feedback showed that the product made sense to me, with my food-science background, but not always to everyday users:

One tester didn't understand what the app does from the sign-up screen. She isn't from the food world and assumed it was a different kind of app. Change: add one clear line at sign-up, for example "Scan any food and see if it fits your goals."
Users found it too detailed. Change: lead with one big, plain answer (such as "Good fit for your goal"), with the details below for anyone who wants them.
"Lose weight" needed explaining. Most people think in calories and portions, so results for this goal should lead with those.
Screens were text-heavy. This led to expandable explanations and a clearer content hierarchy on mobile.
9. Success Metrics

Metrics I plan to measure as testing grows:

Barcode scan success rate.
Share of new users who reach their first recommendation.
Activation: users who scan 3+ products in their first session.
Engagement with the "How calculated" explanation.
Repeat use and retention after one week.
Frequency of "Unavailable" results caused by missing data.
10. What I'm Exploring Next
Local alternatives: suggest healthier options available in the user's own country, starting with Canada.
Weekly treat allowance: help users see how a treat fits into their goals over a week, not just in one scan.
Simpler first experience: apply the onboarding and results changes from user feedback.
Wider testing: grow to 30–50 testers and track the metrics above.
11. Lessons Learned
Trust is a product requirement. Data quality has to come before personalized recommendations.
Simple experiences take hard decisions. Making the interface simpler meant deciding what to leave out.
I am not my user. My food-science background made the app feel obvious to me, and real users showed me where it wasn't.

Skills demonstrated: product discovery · competitive analysis · product strategy · MVP definition · requirements and acceptance criteria · prioritization · UX design · data quality · functional testing · user feedback and iteration · AI-assisted development
