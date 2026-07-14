# Could Sentence Builder 🧩

An interactive web game to practice the modal verb **could** in English — build scrambled sentences in the correct order, get instant feedback, and see your final score. Built for English learners.

**Play it here:** `https://joanescalante16.github.io/Could-Sentence-Builder/`


---

## How it works

1. Enter your name to start.
2. Read the scrambled words on screen.
3. Tap the words in the order you think is correct to build the sentence.
4. Press **Check** to see if you got it right.
5. Get instant feedback: whether you were correct, the sentence type (Affirmative / Negative / Interrogative), the correct sentence, and a short grammar tip.
6. After 5 sentences, see your final score along with a review of every sentence.

## What it covers

The game practices the three structures of **could**:

| Structure | Example |
|---|---|
| Affirmative | She could speak French fluently. |
| Negative | I couldn't finish the homework yesterday. |
| Interrogative | Could you close the window, please? |

It also reinforces the different **uses** of could: past ability, polite requests, and possibility.

## Tech

- Single HTML file — no build steps, no installs, no dependencies to manage.
- Works on desktop and mobile.

## Run it locally

Just download `index.html` and open it in any browser — no server required.

## Customize the sentences

Open `index.html` and find the `SENTENCES` array near the end of the `<script>` section. Each sentence has:

```js
{
  words: ["She","could","speak","French","fluently."], // correct word order
  type: "Affirmative",                                  // Affirmative | Negative | Interrogative
  tip: "Structure: subject + could + base verb..."       // feedback shown after checking
}
```

Edit, add, or remove entries to fit your own lesson.

## License

Free to use, modify, and share for educational purposes.
