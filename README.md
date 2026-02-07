# T.E.P.A.T. — Live Transport & Fares 🚌

<p align="center">
  <img src="https://tepat.tzhub.site/assets/logo.png" alt="T.E.P.A.T. Logo" width="120">
</p>

<p align="center">
  <strong>Intelligent Transport System for Kuala Lumpur & Selangor</strong><br>
  Track buses, MRT, LRT, and BRT across Klang Valley with live positions and weather-aware ETAs.
</p>

---

## 📖 The Project
**T.E.P.A.T.** is a solo-developed intelligent assistant designed to take the stress out of commuting. It transforms complex, high-frequency transit data into a clean, mobile-responsive dashboard. Whether it's peak-hour traffic or a sudden storm, T.E.P.A.T. keeps you informed so you can plan your journey with confidence.

## 🚀 Live Features (As seen on Site)
* **Journey Planner:** Check routes and total fares with a custom departure time selector.
* **Live Transport Map:** A real-time visual map of vehicle positions across the Klang Valley.
* **ETA Countdowns:** Accurate, live-updating minutes until your next ride arrives.
* **Weather Impact:** A unique feature that calculates how current weather (temperature/storms) will affect arrival times.
* **Peak Hour Detection:** Smart alerts that recommend alternative routes when congestion is detected.
* **Nearby Stops:** Location-based tracking to find the closest transit hubs instantly.

## 🛠️ Technical Deep-Dive
* **Core Engine:** Built with **Laravel** for a robust, scalable backend.
* **Live Data:** Consumes **GTFS Realtime** feeds via the **Malaysia Open API** and **Prasarana**.
* **Mapping & UX:** * **Google Maps API** for live positioning and route polylines.
    * **Open-Meteo API** for real-time weather integration.
* **Frontend:** A fully **Mobile-Responsive** design optimized for commuters on the move.
* **Update Frequency:** Data refreshes every **30 seconds** to ensure high-precision tracking.

## 👨‍💻 Developer
* **Aiman Zakuwan** – Final Year Intelligent Systems Engineering Student at UiTM Shah Alam.

---

### 🚦 System Status
| Service | Status |
| :--- | :--- |
| **GTFS Realtime** | Live & Active |
| **Weather Impact Calc** | Functional |
| **Fare Estimation** | Live |

*Built with ❤️ for the Malaysian commuting community.*
