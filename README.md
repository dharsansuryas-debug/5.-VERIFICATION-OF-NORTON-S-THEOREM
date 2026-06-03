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

<img width="1280" height="1103" alt="image" src="https://github.com/user-attachments/assets/2bbc81d2-3e56-4aba-befb-cca9f27c786e" />


**To measure RTh or RN**

<img width="1280" height="1065" alt="image" src="https://github.com/user-attachments/assets/1ead2a6d-f78d-43d0-b055-b0b95d7355ff" />


**To measure IN or Isc**

 <img width="1280" height="677" alt="image" src="https://github.com/user-attachments/assets/456a69d5-e454-41d1-b988-8475b9c07907" />

**Thevenin’s equivalent circuit**

<img width="1280" height="656" alt="image" src="https://github.com/user-attachments/assets/82c24fea-ce72-4f92-a89f-fefc0aa67473" />

**Norton’s equivalent circuit**

<img width="1280" height="966" alt="image" src="https://github.com/user-attachments/assets/7c39c5c4-c050-4d3d-9351-6fd360fe901e" />

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

<img width="1290" height="455" alt="image" src="https://github.com/user-attachments/assets/c17a1cd3-050d-4547-a2db-57da3950ccc2" />

**TABULAR COLUMN:2**

To measure RTh or RN

<img width="1330" height="552" alt="image" src="https://github.com/user-attachments/assets/67a6806e-0163-4207-a670-c5f636ff838c" />


**TABULAR COLUMN:3**

To measure IN or Isc

<img width="1396" height="534" alt="image" src="https://github.com/user-attachments/assets/8d783d9e-17cc-4361-b6d8-713eaea742ad" />

	
**MODEL CALCULATION:**

Practical value of IL (from tabulation 1) =2.3mA

**Verification of Norton’s theorem**

IL = IN * RN / ( RN+ RL ) = 2.43mA

Theoretical calculation of IL ,IN and RTh(RN) for the given circuit:
 
<img width="565" height="679" alt="image" src="https://github.com/user-attachments/assets/6346dea9-58ee-4743-8374-9be7af4ad0d8" />
<img width="868" height="671" alt="image" src="https://github.com/user-attachments/assets/6664f0ba-e343-4056-858e-25eccdcdf216" />
<img width="391" height="472" alt="image" src="https://github.com/user-attachments/assets/da376e9c-914a-415f-9245-8f5ed9e88f1c" />


**RESULT:**

Thus Thevenin’s and Norton’s theorem is verified practically and theoretically.
