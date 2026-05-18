Welcome to the FATEPREDICTOR, by THORIUMPROJECTS.  This is the beta version of the project. Animations/bugs may be prevalent. Code was restructured by Sonnet 4.6 for bug checks and polishing, please contact if bugs persist. 


#  Fate Predictor (Just for Fun)

A playful, interactive HTML-based “fate predictor” that generates a fictional life outcome for a selected person using a dynamic elimination system inspired by classic counting games.

##  Concept

This project simulates a humorous “prediction engine” that determines a person’s future across multiple life categories—relationships, lifestyle, and more. It’s designed purely for entertainment and creativity.

At the center of the experience is a geometric elimination mechanic: a concentric circle system that iteratively removes options until only one remains per category, forming a complete “fate.”

---

##  How It Works

###  Person Selection

* A customizable **“Person X”** is displayed in the top-left corner.
* Users can input and change the name via a text box.

---

###  Partner Axis (Top X-Axis)

* Displays potential partners: *Person 1, Person 2, Person 3, ...*
* Users can:

  * Edit names via text inputs
  * Dynamically add more partners using a button

---

###  Children Axis (Left Y-Axis)

* Numeric scale representing the number of children
* Ranges from **1 to as many as desired**
* Acts as one dimension of the final fate outcome

---

###  Housing Axis (Right Y-Axis)

* Lists possible living situations from top to bottom:

  * Shack
  * No Home
  * Apartment
  * Mansion
  * Condo
  * Bungalow

---

###  Relationship Type Axis (Bottom X-Axis)

* Displays how the relationship plays out:

  * Married
  * Just friends (with benefits)
  * NCMO (No Commitment Make-Out)
  * Broke up because “Person X cheated then got back together”

---

## Elimination Mechanic (Core Feature)

At the center is a **concentric circle system**:

* The number of rings determines the elimination interval

  * Example: 2 rings → every 2nd option is eliminated
* Elimination proceeds **clockwise across all axes**
* Each axis is reduced step-by-step until only one option remains

This creates a dynamic, game-like selection process similar to a counting wheel.

---

## 🧾 Final Output

Once all categories resolve, the program constructs a sentence:

> *“Person X will be with Person 1, married, living in a bungalow, with 3 children.”*

---

## UI

* Clean, aesthetic interface
* Interactive inputs across all axes
* Visually engaging central animation (concentric circles)
* Smooth, intuitive user experience

---

## Disclaimer

This project is purely for fun and has no real predictive power. Outcomes are randomly generated through elimination logic. 

---
