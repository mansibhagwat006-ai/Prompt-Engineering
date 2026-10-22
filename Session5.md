# SESSION 5

## Task 1: Trending Dishes on Zomato (checking for made-up information)

**Prompt:**

```
List the top 5 trending dishes on Zomato in Ahmedabad right now.
```

**AI's response:**

> I couldn’t verify Zomato’s live, city-specific trending rankings for Ahmedabad right now, but these five dishes are good candidates based on available food-trend data and local food listings. 

India News - Business Standard
+2



1. Chaat — Pani puri, sev puri and aloo tikki chaat.
2. Biryani — A popular, filling rice meal.
3. Dosa — Masala dosa and Mysore masala dosa.
4. Pizza — Cheese-loaded and paneer-topped varieties.
5. Sandwiches — Grilled sandwiches and cheesy fillings.
Note: This is an indicative list, not a verified real-time ranking from Zomato. Actual trends can vary by neighbourhood and time of day.

**How to check it for hallucination:**

| Check | What to do | Result |
|-------|------------|--------|
| Is the list "real-time"? | Zomato's trending list changes often and a chatbot without browsing cannot see it. If the AI confidently gives a list without saying this, it is guessing. | No. The answer clearly stated that the list was not a verified live Zomato ranking. |
| Do the dishes exist? | Open Zomato, set the location to Ahmedabad and compare. | Mostly yes. Dishes such as chaat, biryani, dosa, pizza and sandwiches are listed among food options in Ahmedabad. |
| Any made-up numbers? | Look for order counts, ratings or percentages with no source. | No. No order counts, ratings or percentages were provided in the list. |
| Any invented restaurant names? | Search each restaurant on Zomato or Google Maps. | No restaurant names were given. Only dish names were listed. |
| Did it admit any limits? | A good answer says it has no live access to Zomato data. | Yes. It explicitly said the list was indicative and that live Zomato rankings could not be verified. |


---

## Task 2: Summary Using Only the Given Text

**Prompt:**

```
Summarize the IPL 2023 final match. Only use the text provided below. Do not
add anything else, no scores, players, venue or any other detail from your own
knowledge. If something is not in the text, don't mention it.

Text: "Chennai Super Kings won the IPL 2023 final against Gujarat Titans by 5
wickets."
```

**AI's response :**

> Chennai Super Kings won the IPL 2023 final against Gujarat Titans by 5 wickets.

**Does it stick to the given data?** Yes. The response only repeats the two facts in the text: the winner and opponent, and the margin of 5 wickets. It adds no venue, scores, players or dates. If an AI adds anything beyond these (like the match location or who scored the winning runs), that is extra information that wasn't in the provided text.

---

## Task 3: Product Description with a Verification Follow-Up

**Prompt 1 (generate the description):**

```
Write a Flipkart product description for a new wireless earbud. Keep it under
80 words and mention its main features.
```

**AI's response:**

> Product: Wireless Earbuds

Description: Enjoy powerful bass, crystal-clear calls and a comfortable fit with these wireless earbuds. Bluetooth connectivity ensures quick pairing, while the long-lasting battery keeps your music going all day. Touch controls make it easy to manage calls and tracks, and the compact charging case is perfect for travel. Ideal for music lovers, gaming and everyday use.

**Prompt 2 (verification follow-up):**

```
Is all the information in your previous answer based on real data or did you
make any assumptions? List any details you invented.
```

**AI's response:**

>The previous answer was a generic product description, not based on verified data for a specific earbud model. I assumed typical wireless earbud features.

Details I invented or assumed:
- Powerful bass — not verified.
- Crystal-clear calls — not tested or verified.
- Comfortable fit — no product-specific evidence.
- Bluetooth connectivity and quick pairing — assumed standard features.
- Long-lasting, all-day battery — no battery specifications provided.
- Touch controls — not confirmed.
- Compact charging case — assumed.
- Suitable for gaming and travel — general marketing claims, not verified.
No specific product model or technical specifications were provided, so these claims should not be treated as factual.

To make the description accurate, I would need the actual product details, such as battery life, Bluetooth version, control type, sound features, and charging-case specifications.

**What to look for:** since no product details were given, every spec in the first answer (battery hours, Bluetooth version, drivers, water resistance) has to be invented. A good second answer admits this and lists those details. If the AI claims everything was real, that is a problem.

---

## Task 4: Refactored Prompt to Reduce Hallucination

**Original prompt:**

```
Write a review of the latest iPhone.
```

**Improved prompt:**

```
Write a short review of the latest iPhone model currently listed on Apple's
official website (apple.com). Use only the specifications and features stated
on Apple's official product page. Do not use rumours, third-party reviews or
your own assumptions. If you cannot access the website, say so instead of
guessing. Cover the display, camera, battery and price as listed by Apple, and
write "not listed on Apple's website" for anything you cannot find.
```

**Why it reduces hallucination:** it limits the AI to one official source, names exactly what to cover, and gives it permission to say "not found" instead of filling gaps with guesses.

---

## Task 5: BookMyShow Movie Summary Generator (with sources)

**Prompt:**

```
You are the summary generator for BookMyShow. Summarize the movie "[movie name]"
for a user deciding whether to book a ticket.

Rules:
1. Write 4 to 5 short bullet points covering the genre, plot (no spoilers),
   main cast, director and runtime.
2. After each fact, mention the source URL.
3. If you cannot find a source for a fact, write "source not found" instead of
   guessing.
4. Do not add any fact that you cannot source.
5. At the end, state which points you are least sure about.
```

**AI's response:**

> - Genre: Romance, drama, and action/adventure. Source: Paramount Pictures
- Plot: A young artist, Jack, and a wealthy young woman, Rose, fall in love aboard the ill-fated Titanic during its maiden voyage. Source: AFI
- Main cast: Leonardo DiCaprio as Jack Dawson, Kate Winslet as Rose DeWitt Bukater, and Billy Zane as Cal Hockley. Source: IMDb
- Director: James Cameron. Source: 20th Century Studios
- Runtime: Approximately 3 hours 14–16 minutes, depending on the source. Source: Paramount Pictures
Least sure about: The exact runtime, as official and other film listings differ slightly.

**How to check the response:**

- Open every URL the AI gives. Some AIs invent links that look real but lead to nothing.
- Check that each fact actually appears on the page it cites.
- Count how many facts say "source not found". Honest answers will have some.
- Confirm the cast, director and runtime against BookMyShow or IMDb.
