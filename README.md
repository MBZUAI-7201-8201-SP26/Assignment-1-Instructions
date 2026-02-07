## Assignment (Lab) 1: What to Submit + Cross-Validation (Total: 50 Points)

This document explains:
- how to join the GitHub Classroom,
- what you need to complete for Lab 1, and
- how the cross-validation (peer check) works.

Please read it carefully before starting!

---

## Part 0: Join the GitHub Classroom

1. Join the assignment by accepting the invitation here: https://classroom.github.com/a/dUXw7fch  

2. You will be asked to link your GitHub account to your name (You may encounter a **“Repository Access Issue”** error, check below):
   <img width="686" height="392" alt="image" src="https://github.com/user-attachments/assets/603dd71c-d204-4905-8cca-6cb879bab58f" />

3. GitHub will send an invitation email to the address linked to your GitHub account. Make sure you log into the **correct GitHub account** and accept the invitation from that email.

   If you do not accept the invitation, you may see a **“Repository Access Issue”** message:
   <img width="1345" height="639" alt="image" src="https://github.com/user-attachments/assets/dde99b43-0604-49e3-8017-b1800d6900ee" />

4. After accepting, you will get a **private GitHub repository** for this assignment under our class organization.
   - This repo is only visible to you and the instructors/TAs.
   - Submission is done by pushing commits to it.
   - You can check the assignment deadline in the repo page.

---

## Part 1: Do the Lab (40 Points)

1. Read the Lab 1 instructions here:
   https://docs.tenstorrent.com/tt-metal/latest/tt-metalium/tt_metal/labs/matmul/lab1/lab1.html
   - Some figures may not display properly, click on it to show the full figure.

2. Complete the exercises by following the instructions in the lab document.

3. Save evidence that your code runs correctly, such as terminal outputs, logs, screenshots etc.

4. You will need to submit your source codes for the two following exercises particularly:
   - **Exercise 1:** Tiled matrix multiplication on a general CPU
   - **Exercise 7:** Tiled matrix multiplication on Tenstorrent

5. Commit and push your **source code** for the exercises to your GitHub Classroom repository, along with the evidences.

6. Write a clear and simple `README.md` that explains how to reproduce your results using your code (important for Part 2).

---

## Part 2: Cross-Validation (Peer Review) (10 Points)

You will be randomly assigned with another classmate (details will be announced later).

For cross-validation, you will:

1. Grant access to the classmate you are assigned to.
1. Follow your assigned classmate’s `README.md` and try to reproduce their results.
1. Check whether your output matches what they claim.
1. Note down if something does not work or if the results does not match with the evidence provided.
1. Save evidence of your cross validation attempts and open a pull request on your assigned classmate's repo.
1. Feel free to use the checklist below!
   
---

## Lab 1 Checklist

### Part 1: Your Lab

- ⬜ Completed **Exercise 1** (CPU tiled matrix multiplication)
- ⬜ Completed **Exercise 7** (Tenstorrent tiled matrix multiplication)
- ⬜ Saved run evidence (logs, terminal output, screenshots, etc.)
- ⬜ CPU tiled matmul matches the reference implementation
- ⬜ Tenstorrent tiled matmul matches the reference implementation
- ⬜ Clear instructions to reproduce your results
- ⬜ All work committed and pushed to your GitHub Classroom repository

### Part 2: Cross-Validation

- ⬜ Read and followed the assigned classmate’s `README.md`
- ⬜ Successfully reproduced and verified their results
- ⬜ Documented and pushed your reproduction attempts
