---
id: 67a9f44e6dcabb0c402a9bfb
title: Task 5
challengeType: 19
dashedName: task-5
---

<!-- (Audio) Bob: Do you think that's a good idea? -->

# --instructions--

Listen to the audio and answer the question below.

# --questions--

## --text--

What does Bob want to know?

## --answers--

If employees have already bought office furniture.

### --feedback--

Bob isn't asking for confirmation of purchases.

---

How much office furniture costs.

### --feedback--

Bob does not ask about the price.

---

If the company will increase the stipend.

### --feedback--

Bob is not discussing changes to the stipend.

---

If Anna thinks using the stipend for office furniture is a good idea.

## --video-solution--

4

# --explanation--

Bob asks, `Do you think that's a good idea?` This is a way to ask for someone's opinion about a suggestion or plan. Here's other ways to ask for an opinion:

- `Do you think this will work?`

- `What's your opinion on this?`

- `How do you feel about this plan?`

In this dialogue, Bob is referring to employees using the remote work stipend for office furniture. Instead of stating his own opinion, he is asking Anna what she thinks.

# --scene--

```json
{
  "setup": {
    "background": "company1-boardroom.png",
    "characters": [
      {
        "character": "Bob",
        "position": {
          "x": 50,
          "y": 15,
          "z": 1.2
        },
        "opacity": 0
      }
    ],
    "audio": {
      "filename": "B1_11-1.mp3",
      "startTime": 1,
      "startTimestamp": 8.6,
      "finishTimestamp": 10.04
    }
  },
  "commands": [
    {
      "character": "Bob",
      "opacity": 1,
      "startTime": 0
    },
    {
      "character": "Bob",
      "startTime": 1,
      "finishTime": 2.44,
      "dialogue": {
        "text": "Do you think that's a good idea?",
        "align": "center"
      }
    },
    {
      "character": "Bob",
      "opacity": 0,
      "startTime": 2.94
    }
  ]
}
```
