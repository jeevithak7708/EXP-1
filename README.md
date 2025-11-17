# EXP-1
EXPT NO: 1	VERIFICATION OF KIRCHHOFF’S LAWS
AIM
a.   To verify Kirchhoff’s Voltage Law (KVL) for the given circuit. 
b.   To verify Kirchhoff’s Current Law (KCL) for the given circuits.

APPARATUS REQUIRED:
S.No.	Components	Range	Quantity
1	Resistor	1kΩ	3
2	Voltmeter (DC)	0-30V	3
3	Ammeter (DC)	(0-200)mA	3
4	Bread Board		1
5	Regulated Power Supply	(0-30)V	1
6	Connecting wires		As required

THEORY:
KVL: Kirchhoff's voltage law states that the sum of the voltage differences around any closed loop in a circuit must be zero. A loop in a circuit is any path that ends at the same point at which it starts.
KCL:
Kirchhoff's Current Law (KCL) Kirchhoff's Current Law states that the algebraic sum of the currents entering and leaving a node is equal to zero. By convention, currents entering the node are positive, and those leaving a node are negative


PROCEDURE:
a.   KVL:
1.   Connect as per the circuit diagram.
2.   Check if the RPS voltage is set to zero voltage.
3.   Check all the meters for null position.
4.   Switch on the RPS.
5.   Set the input voltage to a value between 0V to 30V.
6.   Record the voltage values shown in the voltmeter connected across each resistor.
7.   Take readings for different values of input voltage and tabulate them.


b.  KCL:
1.   Connect as per the circuit diagram.
2.   Check if the RPS voltage is set to zero voltage.
3.   Check all the meters for null position.
4.   Switch on the RPS.
5.   Set the input voltage to a value between 0V to 30V.
6.   Record the voltage values shown in the ammeter connected to each resistor.
7.   Take readings for different values of input voltage and tabulate them.
   
CIRCUIT DIAGRAM:

a.   KVL:
 <img width="1554" height="859" alt="Screenshot 2025-11-12 154321" src="https://github.com/user-attachments/assets/824c2d65-1990-4372-a987-00742b1e18ee" />
b.  KCL:
 <img width="1573" height="883" alt="Screenshot 2025-11-12 160528" src="https://github.com/user-attachments/assets/27cdb5d0-430d-4145-b56b-6e703956fe25" />

Calculation:

a.   KVL:
 
$$V=V_{1}+V_{2}+V_{3}$$

$$100=IR_{1}+IR_{2}+IR_{3}$$

$$R_{eq}=R_{1}+R_{2}+R_{3}$$

$$R_{eq}=180$$

$$I=V/R_{eq}=100/180$$

$$I=0.556 A$$

$$V_{1}=IR_{1}=0.556\times30=16.68 V$$
$$V_{2}=IR_{2}=0.556\times50=27.8 V$$
$$V_{3}=IR_{3}=0.556\times100=55.6 V$$

$$100V=16.68V+27.8V+55.6V$$
$$100V=100V$$

$$Hence Proved$$

b.  KCL:

$$I_{30\Omega}=I_{50\Omega}+I_{100\Omega}$$

$$I_{30\Omega}=(100-V)/30$$

$$I_{50\Omega}=V/50$$

$$I_{100\Omega}=V/100$$

$$(100-V)/30=V/50+V/100$$

$$V=52.63V$$

$$I_{30\Omega}=(100-52.63)/30=1.58A$$

$$I_{50\Omega}=52.63/50=1.05A$$

$$I_{100\Omega}=52.63/100=0.53A$$

$$Hence  Proved$$

Tabulation:

a.   KVL:
 
| Type         | Source (V) | V<sub>30Ω</sub> (V)  | V<sub>50Ω</sub> (V) | V<sub>100Ω</sub>(V)  | V<sub>30Ω</sub> + V<sub>50Ω</sub> + V<sub>100Ω</sub> (V)|
|--------------|------------|----------------------|---------------------|----------------------|---------------------------------------------------------|
| Theoretical  | 100        | 16.88V               | 21.78V              | 55.6V                | 100.05                                                  |
| Practical    | 100        | 16.88V               | 21.78V              | 55.6V                | 100.08                                                  |

b.  KCL:
| Type         | I<sub>30Ω</sub> (A)  | I<sub>50Ω</sub> (A)  | I<sub>100Ω</sub> (A)  | V<sub>A</sub> (V) |
|--------------|----------------------|----------------------|-----------------------|-------------------|
| Theoretical  | 1.58A                | 1.05A                | 0.53A                 | 52.63V            |
| Practical    | 1.58A                | 1.05A                | 0.53A                 | 56.63V            |

RESULT:

Thus, for the given circuit, Kirchhoff’s Laws, (a) KVL and (b) KCL are proved.
