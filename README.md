# 5.VERIFICATION-OF-NORTON-S-THEOREM

**AIM:**

To verify Norton’s theorem practically and theoretically for the given DC circuit.

**APPARATUS REQUIRED:**

1.	Regulated Power supply ( RPS)	(0-30 V)	1
2.	Voltmeter	(0-30 V) MC	1
3.	Ammeter	( 0 - 10 mA) MC	1
4.	Resistors	470 Ω 560 Ω 1 K Ω	2 1 1
5.	Bread board	---	1
6.	Multimeter	---	1

**THEORY:**

**NORTON’S THEOREM:**

Norton’s theorem states that, ‘a linear two-terminal circuit can be replaced by an equivalent circuit consisting of a current source, IN (=Isc) in parallel with a resistor RN (= RTh), where IN (=Isc) is the short-circuit current through the load terminals and RN is the equivalent resistance at the load terminals when the independent sources are turned off.Norton’s Current, IN or Isc:
It is the short-circuit current through the load terminals. i.e., IN = Isc

Norton’s Resistance, RN:It is the look-back resistance across the load terminals when all the sources are replaced by their internal resistances. An ideal voltage source is replaced by short- circuiting as its internal resistance is zero. An ideal current source is replaced by open- circuiting as its internal resistance is infinity.
 
**CIRCUIT DIAGRAM: VERIFICATION OF NORTON’S THEOREM**

**To measure IL**

<img width="1280" height="1103" alt="image" src="https://github.com/user-attachments/assets/abcd25a3-ac2e-46fe-96ee-b3956b27a5fe" />

**To measure RTh or RN**

<img width="1280" height="1065" alt="image" src="https://github.com/user-attachments/assets/94022bac-c751-41e2-936d-6cb1f56afcae" />


**To measure IN or Isc**

 <img width="1280" height="677" alt="image" src="https://github.com/user-attachments/assets/8d380e01-0d22-4a95-ade4-3ce2d6ada899" />

**Thevenin’s equivalent circuit**

<img width="1280" height="656" alt="image" src="https://github.com/user-attachments/assets/d71c03ca-8107-429a-92e2-70ecc5267545" />

**Norton’s equivalent circuit**

<img width="1280" height="966" alt="image" src="https://github.com/user-attachments/assets/411e5f4d-1856-49bd-b828-41d76353bc48" />

**PROCEDURE:**

1.	Make the connections as per the Circuit Diagram:1

2.	Vary the RPS and set an input voltage of 10V.

3.	Note down the voltmeter reading (Vi) and ammeter reading (IL) in Tabular Column 1.

4.	Switch off the supply and make connections for Circuit Diagram 2.

5.	Measure the Thevenin’s resistance RTh= Norton’s resistance RN .

6.	Switch off the supply and make connections for Circuit Diagram:3.

7.	Set an input voltage of 10V in the RPS and note down the voltmeter readings Vi and VTh(=Voc) in Tabular Column:3

8.	Switch off the supply and make connections for Circuit Diagram 4.

9.	Set an input voltage of 10V in the RPS and note down the voltmeter reading Vi and Ammeter reading IN (= Isc) in Tabular Column 4.

10.	Draw the Thevenin’s equivalent circuit and Nortons’s equivalent circuit as shown in circuit diagrams 5 & 6 respectively.

11.	Calculate the IL value using the formula

   	Thevenin’s Theorem IL = VTh/ ( RTh+ R L)

   	Norton’s Theorem IL = IN * RN / ( RN + RL )

12.	Theoretically verify the Norton’s theorem.

**TABULAR COLUMN: 1**

To measure I L

<img width="1290" height="455" alt="image" src="https://github.com/user-attachments/assets/d11b238b-54be-407e-9571-e263affabf54" />

**TABULAR COLUMN:2**

To measure RTh or RN

<img width="1330" height="552" alt="image" src="https://github.com/user-attachments/assets/d03cb9cf-b8ed-48f7-83c0-869704fb3d41" />


**TABULAR COLUMN:3**

To measure IN or Isc

<img width="1396" height="534" alt="image" src="https://github.com/user-attachments/assets/49148d42-27e7-46c7-9f22-98ae49493c88" />

**MODEL CALCULATION:**

Practical value of IL (from tabulation 1) =2.3mA

**Verification of Norton’s theorem**

IL = IN * RN / ( RN+ RL ) = 2.43mA

Theoretical calculation of IL ,IN and RTh(RN) for the given circuit:
 
<img width="565" height="679" alt="image" src="https://github.com/user-attachments/assets/26248458-b108-4365-8231-851bf94dcd7a" />
<img width="868" height="671" alt="image" src="https://github.com/user-attachments/assets/d4073f52-2dbb-409d-8772-e2cea4d08b22" />
<img width="391" height="472" alt="image" src="https://github.com/user-attachments/assets/44f7d9ef-f1ef-4d5f-94cc-e76c71e00b21" />


**RESULT:**

Thus Thevenin’s and Norton’s theorem is verified practically and theoretically.
