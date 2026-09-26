# laboratorna Work #3 - SDLC
Variant 21 — Sleep Time Calculator

1. Planning

Product goal:

Create a simple Sleep Time Calculator application that helps users determine the recommended bedtime or wake-up time based on 90-minute sleep cycles.

2. Requirements Analysis (User Stories)

1. As a user, I want to enter my wake-up time so that I can get a recommended bedtime. (Must have)

2. As a user, I want to enter my bedtime so that I can get a recommended wake-up time. (Must have)

3. As a user, I want to choose the number of sleep cycles so that I can get a more accurate result.

4. As a user, I want to see the sleep duration in hours and minutes so that I can understand how long I will sleep.

5. As a user, I want to have a simple and clear interface so that I can easily use the calculator.

3. Design (Prototype)

The prototype consists of two main screens.

Screen 1 — Main Screen:

The user can enter the wake-up time, select the number of sleep cycles and press the Calculate button.

Screen 2 — Result Screen:

The application displays the recommended bedtime, number of sleep cycles and sleep duration.

4. Implementation (Pseudocode)

Calculate bedtime:

1. Set the sleep cycle to 90 minutes.

2. Multiply the number of cycles by 90.

3. Subtract the total sleep time from the wake-up time.

4. Return the recommended bedtime.

Calculate wake-up time:

1. Set the sleep cycle to 90 minutes.

2. Multiply the number of cycles by 90.

3. Add the total sleep time to the bedtime.

4. Return the recommended wake-up time.

5. Testing

Test 1:

Input: Wake-up time 07:00, 5 sleep cycles.

Expected result: Bedtime 23:30.

Status: Passed.

Test 2:

Input: Bedtime 23:00, 5 sleep cycles.

Expected result: Wake-up time 06:30.

Status: Passed.

Test 3:

Input: 2 sleep cycles.

Expected result: Error because the number of cycles should be between 4 and 6.

Status: Passed.

6. Conclusion

The Agile approach is suitable for this project because the application is small and can be gradually improved based on user feedback.

In the future, the application could include sleep history, statistics and reminders.
## Prototype
![Sleep Time Calculator Prototype](./photo-2026-09-26-15-20-42.jpg)
