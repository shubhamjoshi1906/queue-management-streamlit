## 🔗 Live Demo
[Click here to run the app](https://flowgov-ai-gpexv7wlfkgmhyfwtqqjzt.streamlit.app/)

Project Overview: FlowGov AI

FlowGov AI is a predictive "Smart Queue" management ecosystem. Unlike traditional systems that simply hand out paper tokens, FlowGov uses Machine Learning to transform unpredictable waiting rooms into streamlined, data-driven environments. It is specifically engineered for high-volume public sectors, such as government hospitals (OPDs), passport offices, and transit hubs.

1. The Core Innovation: From Reactive to Predictive

Current systems are reactive—they track who is waiting but cannot predict when they will be served. This leads to 2–4 hour wait times, physical overcrowding, and staff burnout.

FlowGov AI shifts the philosophy to "Just-In-Time Arrival." By providing real-time, high-accuracy wait estimates, the system allows citizens to arrive exactly when they are needed, clearing physical lobbies and reducing infection risks in medical settings.

2. The Intelligence Engine

The backbone of the project is a Random Forest Regression model. This AI engine was chosen for its ability to handle the "noise" of real-world environments, such as sudden emergencies, staff breaks, or "no-shows."

    Statistical Precision: The model achieves an R2 Score of 0.9819, meaning it explains over 98% of wait-time variability.

    Minimal Margin of Error: The Mean Absolute Error (MAE) is approximately 3.51 minutes, ensuring that when a patient is told they have a 20-minute wait, the prediction is statistically validated.

    Feature-Rich Inputs: The AI considers queue length, staff on duty, department-specific velocity, and even "Zipper Logic" (fairly reinserting patients who missed their initial call).

3. Scalability & Operational Impact

FlowGov AI is built as a modular, cloud-ready solution designed for rapid deployment across various scales:

    Public Health: Reducing OPD crowding by 15–25%, leading to better doctor utilization and lower patient conflict.

    Civil Services: Application in RTOs, passport offices, and court systems to optimize citizen flow.

    Data-Driven Governance: Provides administrators with a "Surge Prediction Radar" and peak-hour analytics to make informed staffing decisions rather than relying on guesswork.

The Bottom Line

FlowGov AI isn't just a digital version of a paper ticket; it is operational intelligence. It replaces the chaos of manual tracking with a sophisticated forecasting layer, ensuring that public infrastructure functions with the precision of a modern data-driven enterprise.