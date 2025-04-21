# JKFLIPFLOP-USING-IF-ELSE

**AIM:** 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**JK Flip-Flop**

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/a649c30b-232b-4558-b188-fd6c09845180)


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.
![WhatsApp Image 2025-04-21 at 22 33 34_d4af3fda](https://github.com/user-attachments/assets/0e46282b-1867-4855-8f7f-4885bb9ba08c)


 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
![image](https://github.com/user-attachments/assets/259f0e38-64ba-480f-97b7-910ea258cdb8)


By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 

![image](https://github.com/user-attachments/assets/0be3b87a-2011-4db4-88df-0c1f9de88e07)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

**Procedure**


![image](https://github.com/user-attachments/assets/49265f13-38f0-41aa-a0a7-0c4759dc7d57)

**PROGRAM**

![image](https://github.com/user-attachments/assets/077f1ddf-9a5d-43a6-a3cd-e9a8572aa354)



**RTL LOGIC FOR FLIPFLOPS**
![image](https://github.com/user-attachments/assets/dd7e1168-f380-47c8-990d-dd0b17ec03f5)


**TIMING DIGRAMS FOR FLIP FLOPS**
JK FLIPFLOP:
![image](https://github.com/user-attachments/assets/94167221-299c-43f4-babe-aba16e34a68f)


**RESULTS**
Thus,the code executed successfully.
