# Standard Procedure: Daily Fault Checking and Summary

## 1. Purpose

To consistently check the Daily Monitoring dashboard, identify all faults, and provide a detailed summary of fault codes 3, 2, 329, and 41.

## 2. Scope

This procedure applies to the daily review of faults shown in the Daily Monitoring dashboard.

## 3. Daily Checking Schedule

Perform the fault check four times every working day:

| Check | Scheduled Time |
|---|---|
| Check 1 | 9:00 AM |
| Check 2 | 11:00 AM |
| Check 3 | 1:00 PM |
| Check 4 | 3:00 PM |

Use the local site time. At each scheduled time, record the checking time and compare the results with the previous check to identify new, repeated, pending, and recovered faults.

## 4. Open the Dashboard

At each scheduled check time, complete the access steps before starting the fault review. The automatic run sequence is **Refresh → Sign In if required → Run the checking process**:

1. Refresh the Daily Monitoring website.
2. If the session has expired, click **Sign In** whenever the login page appears. The click may be performed even when the browser does not visibly show the credentials.
3. After sign-in, refresh the page once more if needed so the current dashboard data is loaded.
4. Select **Today Fault**.
5. Disable **“รวมรายการที่ทำแล้ว”** so records already marked **Completed** are excluded.
6. Set the **Fault Type** filter to **ทั้งหมด / All**.
7. Only after these steps are complete, start **Check All Faults First**.

If the password field is empty or sign-in cannot be completed, stop and ask the user to sign in directly in the browser. Do not store, request, or enter passwords in chat.

### Manual “Run now” Command

When the user sends **“Run now”**, perform this sequence automatically:

1. Refresh the page.
2. Check whether the sign-in page appears.
3. Click **Sign In** automatically whenever the login page appears.
4. If sign-in remains unsuccessful because credentials are missing, stop and ask the user to sign in directly; never request, read, store, or handle the password in chat.
5. After successful sign-in, refresh the dashboard if needed.
6. Confirm completed records are excluded, select **All** faults, and start the review.
7. Continue with the full fault-checking and reporting procedure below.

## 5. Check All Faults First

Record the following information for incomplete/uncompleted records only:

- Date and checking time
- Total fault occurrences
- Fault-code breakdown
- Pending and Recovery status
- Total number of affected plants

Verify that the sum of all fault-code counts equals the dashboard total.

## 6. Review Fault Codes 3, 2, 329, and 41

Repeat the following steps for each fault code:

1. Confirm that **“รวมรายการที่ทำแล้ว”** is disabled.
2. Select the fault code from the **Fault Type** filter.
3. Scroll through the complete list, including the bottom of the list.
4. Record the plant name, equipment name, fault code, action status, and iSolarCloud status.
5. Group records by plant.
6. Count the fault occurrences for each plant.
7. Record the affected equipment and identify repeated faults.

## 7. Summary Format

Every report must use the following order and wording style.

### Report Header

Start with:

> Manual recheck completed with **Completed records excluded**.

Then write:

> Current dashboard:

- Total incomplete faults: **[total]**
- Fault codes 3, 2, 329, and 41: **[combined total]**

### Fault-Code Sections

Create one heading for each monitored code using this format:

> **Fault code 3 — [count]**

Under each heading, list every affected plant as a bullet with its occurrence count:

- [Plant name]: [count]
- [Plant name]: [count]

Repeat for fault codes **2**, **329**, and **41**, even when a code has zero incomplete faults. For zero occurrences, write:

> **Fault code 41 — 0**

> No incomplete faults were found for fault code 41.

### Overall Summary

| Item | Result |
|---|---|
| Date and time checked |  |
| Total fault occurrences |  |
| Total affected plants |  |
| Pending faults |  |
| Recovery faults |  |

### Scheduled Check Log

| Check Time | Total Faults | New Faults | Repeated Faults | Recovery Faults | Pending Faults | Checked By |
|---|---:|---:|---:|---:|---:|---|
| 9:00 AM |  |  |  |  |  |  |
| 11:00 AM |  |  |  |  |  |  |
| 1:00 PM |  |  |  |  |  |  |
| 3:00 PM |  |  |  |  |  |  |

### Fault-Code Summary

| Fault Code | Total Occurrences | Affected Plants | Main Affected Plant |
|---|---:|---:|---|
| All faults |  |  |  |
| 3 |  |  |  |
| 2 |  |  |  |
| 329 |  |  |  |
| 41 |  |  |  |

### Plant-Level Detail

| Fault Code | Plant Name | Occurrences | Affected Equipment | Status |
|---|---|---:|---|---|
| 3 |  |  |  |  |
| 2 |  |  |  |  |
| 329 |  |  |  |  |
| 41 |  |  |  |  |

## 8. Verification

Before sending the report:

- Confirm the **incomplete-fault** total.
- Confirm that completed records are excluded.
- Confirm that all fault-code counts add up to the total.
- Confirm that the entire list was reviewed, including scrolling to the bottom.
- Distinguish total occurrences from the number of unique plants.
- Check that each record has the correct plant and equipment.
- Highlight plants with repeated faults or multiple affected equipment.

## 9. Recommended Report Order

1. Completion/exclusion statement
2. Current dashboard totals
3. Combined total for fault codes 3, 2, 329, and 41
4. Fault code 3 plant breakdown
5. Fault code 2 plant breakdown
6. Fault code 329 plant breakdown
7. Fault code 41 plant breakdown
8. Pending and Recovery status, if available

## 10. Example Conclusion

“Today, [total] fault occurrences were found across [plant count] plants. The most frequent fault was code [code], with [count] occurrences. The plant with the highest number of faults was [plant name]. Pending faults should be prioritized for investigation, followed by confirmation of recovery status.”
