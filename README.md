# EE2033-Integrated-System-Lab-AY2021-Sem2

**1) Task 1 (80%):**

a. You are required to employ Pluto Adalm, RTL-SDR, Analog Discovery 2, LTSPICE,
GNURadio with the given specifications (Design A, B or C) for your group, and design a filter to suppress the interference at Intermediate Frequency (IF, signal from the RTL-SDR).

b. The setup should be similar to what shown in Lecture 1, slide 1-28. The objective is to maximize the PSR, shorten the time taken to achieve the desired number of packets, with cost in mind, i.e. using the least number of opamps with relaxed opamp specifications.

c. You will be evaluated based on the on-site results achieved during the demo and the report (< 15 pages).

d. During the demo, identical desktop, laptop, pluto Adalm, Analog Discovery 2 for TX and RX will be used for all groups under same design specifications.

e. Three TX interference amplitude settings will be used. The given amplitude, 1/3 of the given amplitude, and 1/10 of the given amplitude.

f. You are allowed to change the RX settings on the given laptop based on your earlier findings with your own setup to optimize the result. You are not allowed to fine tune the setting on the spot as this will slow down the examination process.

g. The test message will only be revealed on the evaluation day, and every design will be given different test message.

**2) Task 2 (20%):**

a. Ignoring the interference specifications (By setting interference amplitude to zero),
modify the given grc file to support transmission and reception of two different messages simultaneously (both with OOK modulation) using just only Pluto Adalm and GNURadio for this task.

b. The two messages should be transmitted with different symbol rate as follows (Underline is the design specification given to your team in task 1):
i. Design A symbol rate and Design B symbol rate ii. Design B symbol rate and Design C symbol rate iii. Design C symbol rate and Design A symbol rate

c. User can use a button to swap the two transmission messages. For example, if two separate channels are used to transmit two messages (Channel A for message C and Channel B for message D), the button will swap the channels for the two messages (Channel B for message C and Channel A for message D).

d. You should demo the working of your GRC during evaluation day.

e. You should incorporate detailed grc block print out for this task in the report as well
(1~2 page, in addition to the 15 pages for task 1).

f. You will be evaluated based on your ingenuity in achieving the desired outcome with
compact grc block design.

g. As “OOK Text Sink” can only decode one message at a time, do incorporate a simple
GUI button so we can select which received message string to decode during run time.


# Special Thanks
Lao Zhao & Lin Ran for helping us.
