## Slack

**Team Members:**
- Li Zi Han
- Lim Kang Wei
- Zhang Jing Wen
- Cai Du Yi

**Problem:** 
In the face of a global pandemic, more and more people have to adapt to the work/study from home lifestyle. With an increase in prolonged hours sitting in front of a desk, it is more important than ever for us to detect bad sitting posture and correct it before it results in long-term health implications. As such our team, **NTUC Finest** hope to solve this problem.

**Solution:** 
Using both `TensorFlow` and `Python`, we came up with an algorithm to detect bad sitting posture. Using the algorithm, we implemented it in our application - Slack which is created using `Swift`.

**How to Use the Algorithm:** 
> - Running Run me.ipynb, converts the first two rows from markdown to code.
> - Under action_01, you can add your own datasets for good postures.
> - Under action_02, you can add your own datasets for bad postures.
> - Our provided samples should work fine for a full-on side view of the body.
> - Number of photos for testing can vary, but the python function will have to be altered in **Line 97 range(15**). Change 15 to your number of photos.

**How to Use the App:**
Our Slack app powered by Swift will features a Pomodoro Timer as well as a Posture Detector
> - Select how long you wish to study/work for under the "Time" section.
> - Start the countdown of the timer by pressing the white triangle.
> - Pomodoro Timer can be paused by pressing the "Pause" button.
> - To reset the Pomodoro Timer, select the "Reset" button.

We hope you have enjoyed our application. Constructive feedbacks are welcome! So do let us know how we can improve. 😆
