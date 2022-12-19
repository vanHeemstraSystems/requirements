requirements
# Requirements

Based on "Bridging the communication gap: can tools help? Elke Steegmans/Mieke Kemme" at https://www.youtube.com/watch?v=-83R_RnGDg8

## 100 - Introduction

## 200 - Requirements

## 300 - Building Our Application

Example of a Requirement Specification:

```
**Feature**: Show patient details

**Narrative**;

In order to check the physical condition of a patient,

As a caretaker,

I want to consult his/her personal details.

**Scenario**: the personal details of a registered patient are provided
- GIVEN a patient with the social security number "93051822361", gender "male" and birthdate "1993-05-18"
- AND on "2000-04-10" the patient had a length of "180 cms" and a weight of "75000 grams"
- AND the patient is registered
- WHEN I ask for the details of the patient using his/ehr social security number
- THEN the personal details scoail security number, gender, and birthdate are given
- AND the examination details length, weight, and last examination date are given
- AND the calculated "23.15 BMI" is given
```

## 400 - Conclusion
