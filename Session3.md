# SESSION 3

## Task 1: Zero-Shot Prompt (latest IPL match)

**Prompt used:**

```
Give me a one-line summary of the latest IPL match.
```

**ChatGPT response:**

> The latest IPL match result I could verify was Delhi Capitals defeating Royal Challengers Bengaluru by 6 wickets, chasing 176 with Tristan Stubbs scoring 60* and David Miller finishing the chase.

Note: no example is given, so ChatGPT has to work out the format on its own. If web browsing is off, it may not know the most recent match, so turn on search before running this.

---

## Task 2: One-Shot Prompt (Zomato review)

**Prompt:**

```
I want you to write a Zomato-style food review. Here is one example of the
format I want:

Restaurant: Punjabi Tadka, Navrangpura
Rating: 4/5
Ordered: Butter Chicken, Garlic Naan
Review: The butter chicken was creamy and not too spicy, and the naan came
out hot. Service was a little slow during the dinner rush, but the food made
up for it.
Verdict: Worth a visit for a family dinner.

Now write a review in exactly the same format for a dosa restaurant in
Ahmedabad.
```

**ChatGPT response:**

>Restaurant: Dakshinayan, Ahmedabad
Rating: 4/5
Ordered: Masala Dosa, Mysore Masala Dosa
Review: The dosa was crispy on the outside and perfectly stuffed with spicy potato masala. The coconut chutney and sambhar were flavorful, though the service took a little longer than expected.
Verdict: A great spot for dosa lovers looking for a tasty South Indian meal.

---

## Task 3: Few-Shot Prompt (Flipkart descriptions)

**Prompt:**

```
I'll show you three Flipkart-style product descriptions. Study the tone and
length, then write one for a smartwatch in the same style.

Product: Mobile
Description: Smooth 120Hz AMOLED display, 50MP camera and a 5000mAh battery
that easily lasts a full day. A solid pick for gaming, reels and everything
in between.

Product: Headphones
Description: Wireless over-ear headphones with deep bass and up to 40 hours of
playback. Soft ear cushions keep them comfortable on long calls and longer
playlists.

Product: Shoes
Description: Lightweight running shoes with a cushioned sole and breathable
mesh. Built for daily jogs, with a grip that holds up on wet roads too.

Product: Smartwatch
Description:
```

**ChatGPT response:**

> Product: Smartwatch
Description: Bright touchscreen display, heart rate monitoring and multiple sports modes to track your daily activity. Long battery life and a lightweight design make it a great pick for workouts and everyday wear.

---

## Task 4: Comparing the Three Methods ("Monsoon Vibes" playlist description)

### The three prompts

**Zero-shot**

```
Write a Spotify playlist description for a playlist called "Monsoon Vibes".
```

**One-shot**

```
Write a Spotify playlist description for a playlist called "Monsoon Vibes".
Here is an example of the style I want:

Playlist: Late Night Drive
Description: Empty roads, windows down, and songs that sound better after
midnight. Press play and keep driving.

Now write one for "Monsoon Vibes".
```

**Few-shot**

```
Write a Spotify playlist description for a playlist called "Monsoon Vibes".
Here are examples of the style I want:

Playlist: Late Night Drive
Description: Empty roads, windows down, and songs that sound better after
midnight. Press play and keep driving.

Playlist: Sunday Chill
Description: Slow mornings, strong chai and soft acoustic tracks. Nothing to
do and nowhere to be.

Playlist: Gym Beast Mode
Description: High tempo, heavy beats and zero excuses. Lace up and get it done.

Now write one for "Monsoon Vibes".
```

### Responses

| Method | Response received |
|--------|-------------------|
| Zero-shot | Rainy days, cozy vibes, and songs that hit different. 🌧️🎧 Perfect for window-side views, chai, and getting lost in your favorite melodies. ✨💙 |
| One-shot | Playlist: Monsoon Vibes
Description: Rain on the windows, hot chai, and songs that hit different on cloudy days. Press play and let the rain set the mood. |
| Few-shot | Playlist: Monsoon Vibes
Description: Rainy windows, hot chai and songs that hit different on cloudy days. Get cozy and let the rain take over. |

### Comparison

| Point | Zero-shot | One-shot | Few-shot |
|-------|-----------|----------|----------|
| Length matches Spotify style | _fill in_ | _fill in_ | _fill in_ |
| Tone matches my examples | _fill in_ | _fill in_ | _fill in_ |
| Feels specific to monsoon | _fill in_ | _fill in_ | _fill in_ |

### Most relevant result

_Fill in after running all three prompts._

What I expect to see, to check against the real outputs: zero-shot usually gives a longer, generic description, one-shot copies the length and tone of the single example, and few-shot is the most consistent because three examples show a pattern (short, casual, two or three sentences). If that holds, few-shot is the most relevant, since the model has more to learn the style from. If your results differ, write down what you actually saw.
