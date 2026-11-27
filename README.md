
# Self-Charging Hybrid Electric Bicycle using PMDC Motor

**Department of Electrical Engineering**  
SVERI’s College of Engineering, Pandharpur (A.Y. 2024–25)

---

## 📌 About the Project
This project presents a **Self-Charging Hybrid Electric Bicycle** powered by a Permanent Magnet DC (PMDC) motor. It uses a dynamo generator attached to the wheel to recharge the battery while riding, making daily travel cleaner and less dependent on wall chargers.

---

## ❗ Problem Statement
* **Air Pollution:** Regular petrol vehicles (Internal Combustion Engines) release harmful smoke and pollute the environment.
* **High Power Usage:** Normal electric bicycles require frequent charging from the main power supply, which consumes extra electricity units.
* **Our Solution:** A hybrid e-bicycle that generates its own power while moving to cut down both pollution and grid electricity usage.

---

## 🎯 Objectives
* **Save Electricity:** Reduce the need to plug the bicycle into an external power supply.
* **Reduce Pollution:** Offer a clean, eco-friendly way to travel.

---

## ⚙️ How It Works (Methodology)

The bicycle works using two simple loops:

```text
  [ External Charger ] ──────┐
                             ▼
[ Rear Wheel ] ──► [ Dynamo ] ──► [ Bridge Rectifier ] ──► [ Battery ]
      ▲                                                         │
      │                                                         ▼
[ PMDC Motor ] ◄── [ Accelerator ] ◄── [ Manual Switch ] ◄── [ Controller ]
```

1. **Driving the Bicycle:** Power goes from the **Battery** through the **Controller**, **Manual Switch**, and **Accelerator** to run the **PMDC Motor**, which turns the **Rear Wheel**.
2. **Self-Charging the Battery:** As the **Rear Wheel** spins, it turns the **Dynamo**. The electricity produced goes through a **Bridge Rectifier** to safely charge the **Battery**. An external **Charger** can also be used when needed.

---

## 🛠️ Main Components Used
* PMDC Motor
* Dynamo Generator
* Bridge Rectifier
* Battery & External Charger
* Controller, Manual Switch & Accelerator

---

## ✅ Expected Outcomes & Conclusion
* **Eco-Friendly Ride:** Helps lower environmental pollution with zero fuel emissions.
* **Self-Charging Convenience:** Uses the dynamo generator to recharge the battery on the go without always needing an external electrical supply.

---

## 📄 Presentation
* **[View / Download Project Presentation (PPTX)](Project_Presentation.pptx)**

---

## 📚 References
1. Sveinung Berntsen, Lena Malnes, Aleksander Langaker, Elling Bere — *"Physical activity when riding an Electric assisted bicycle"*, International Journal of Behavioral Nutrition and Physical Activities, April 2017.
2. S. Cairns, Frauke Behrendt, D. Raffo, Chris Kiefer — *"Electrically-assisted bikes: Potential impacts on travel behaviour"*, Transportation Research Part A: Policy and Practice, September 2017.
3. John E. Ware, Kosinski MA, S.D. Keller — *"E-bikes in the Mainstream: Reviewing a Decade of Research"*, January 1993.
4. Chetan Mahadik, Sumit Mahindrakar, Prof. Jayashree Deka — *"An Improved & Efficient Electric Bicycle system with the Power of Real-time Information Sharing"*, 2014.
