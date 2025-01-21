## Invent two words

<html>
  <div style="position: relative; overflow: hidden; padding-top: 56.25%;">
    <iframe style="position: absolute; top: 0; left: 0; right: 0; width: 100%; height: 100%; border: none;" src="https://www.youtube.com/embed/au4cDSYW_EQ?rel=0&cc_load_policy=1" allowfullscreen allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"></iframe>
  </div>
</html>

First, you will collect samples of background noise. This will help your machine learning model to tell the difference between the sounds that you will train it to recognise, and the background noise where you are.

--- task ---

+ Click the **+ Add example** button in **background noise**.

+ Click on the microphone, but don't say anything. Record 2 seconds of background noise. ![Arrow pointing to microphone button](images/record-button.png)

+ Click the **Add** button to save your recording.

---/task---

--- task ---

+ Repeat those steps until you have **at least eight examples** of background noise. ![Bucket filled with 8 background examples](images/8-background.png)

---/task---

Invent two alien words — a word that means "left" and a word that means "right".

Now you will record eight examples of each word so that your machine learning model can learn to recognise them.

--- task ---

+ Click on **+ Add new label** on the top right of the screen and add a label called `left`.

---/task---

--- task ---

+ Click on **+ Add example** inside the box for the new `left` label, and record yourself saying your alien word for "left".

+ Repeat until you have recorded **at least eight examples**.

---/task---

--- task ---

+ Click on **+ Add new label** to create another label called `right` and record eight examples of your alien word for "right".

---/task---
