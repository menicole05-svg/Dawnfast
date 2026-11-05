# Dawnfast 🌅

A visually motivating intermittent fasting tracker. A fast is a night that ends in sunrise — the ring fills with dawn colors as you get closer to your goal.

## Features
Six tabs: **Fast · Water · Meals · Workout · Progress · Me**

- **Water tracker:** set your own glass size and daily goal, quick-add buttons, 7-day chart (+3 sunlight for Zoe when you hit your goal)
- **Creatine tracker:** one tap for your daily dose (default 5 g), streak, last-30-days count, and a 5-week calendar you can tap to fill in missed logs
- **Meal & calorie log:** built-in list of common foods (including Filipino dishes) with estimated calories; log by weight in grams (or by servings), tags, daily calorie target, and eating-window status
- **Macros (MyFitnessPal-inspired):** Goal − Food = Remaining calories, protein/carbs/fat bars and donut, meals grouped into Breakfast/Lunch/Dinner/Snacks, recent foods, and macro goal presets (Balanced, High protein, Low carb, Keto)
- **Workouts (Hevy-inspired):** 277 exercises (barbell, dumbbell, machine, cable, kettlebell, Smith, EZ bar, bands, bodyweight, cardio), gym and home routines, live set logging with previous values, warm-up/drop/failure sets, rest timer, PRs and estimated 1-rep max, history, muscle split, and optional calories burned (estimate, or typed in from your watch or Health app)
- **Grocery planner:** set your daily macros and days, pick foods, type your own prices, and get how many kg/pcs to buy for the week, per-day portions, total cost vs. budget, and cheapest protein per peso (USDA macros)
- **Muscle map (Workout tab):** interactive front/side/back SVG anatomy (female default, male option) with 15 selectable muscle groups colored by an estimated recovery status (recovered, recovering, very sore, no data). Tap a muscle for last trained date, direct and helper sets this week, exercises that target it, recent workouts, and to report soreness. Every exercise maps to primary and secondary muscles; warm-up sets are not counted
- **Weight & waist log:** kg and cm check-ins with a trend chart and change since your first log
- **Live fasting ring** with elapsed time, time remaining, and % of goal
- **Plans:** 13:11, 16:8, 18:6, 20:4, OMAD, 36h
- **Body-stage timeline** (fed state → fat burning → ketosis → autophagy) showing where you are now
- **Motivational messages** that change as you progress, plus a toast when you hit a new stage
- **Streak counter**, stats (total, longest, average), weekly bar chart vs. your goal
- **Your avatar (Me tab):** a customizable character whose body follows your real weight progress toward your goal and whose muscles grow with the exercises you log. Level & EXP, per-muscle stats (Arms, Chest, Back, Core, Legs, Glutes, Cardio), daily quests that follow the routine you train that day (or a rest day), and unlockable outfits and gym gear
- **Zoe, your pet:** she grows from an egg to a Sun Spirit (5 stages) as you earn sunlight by hitting goals
- **Badges** for goals, streaks (3/7/14/30 days) and milestones (fasts and total hours), some unlock outfits for Zoe
- **Streak freeze:** 1 per week, used automatically if you miss a day
- **Confetti + sound** celebrations (sound can be turned off)
- **History** of past fasts, with goal hit/miss chips
- Edit your start time if you forgot to tap Start
- Light & dark mode, works great on phones
- Data is saved in your browser (localStorage) — no account needed

## Food data
Foods marked **✓ USDA** use values from [USDA FoodData Central](https://fdc.nal.usda.gov) (SR Legacy), which is public domain.
Suggested citation: U.S. Department of Agriculture, Agricultural Research Service. FoodData Central. https://fdc.nal.usda.gov

The app also includes 116 plain ingredients (meats, fish, vegetables, oils, sauces, dairy, fruits) from USDA, so you can log what you cook ingredient by ingredient.

Foods marked **Estimate** (mostly cooked Filipino dishes) are approximate values for a typical home-cooked serving.

## Install on your phone (Vercel)
1. Go to [vercel.com/new](https://vercel.com/new) and sign in with GitHub.
2. Import the **Dawnfast** repository. Framework preset: **Other**. No build command needed.
3. Click **Deploy**. Every push to `main` redeploys automatically.
4. Open your Vercel link on your phone:
   - **iPhone (Safari):** Share → **Add to Home Screen**
   - **Android (Chrome):** ⋮ menu → **Install app** / **Add to Home screen**

Dawnfast is a PWA: it opens full screen with its own icon and works offline after the first visit.
Your data is saved on your phone in that browser, so keep using the same browser.

## Run it
It's a single file. Open `index.html` in any browser, or turn on **GitHub Pages** (Settings → Pages → Deploy from branch → `main` / root) to use it on your phone.

> Stage timings are general estimates. Check with a doctor before long fasts.
