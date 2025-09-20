# Smart India Hackathon Workshop
# Date: 20-09-2025
## Register Number: 25017255
## Name: A.ABINESH
## Problem Title
SIH 25010: Smart Crop Advisory System for Small and Marginal Farmers
## Problem Description
A majority of small and marginal farmers in India rely on traditional knowledge, local shopkeepers, or guesswork for crop selection, pest control, and fertilizer use. They lack access to personalized, real-time advisory services that account for soil type, weather conditions, and crop history. This often leads to poor yield, excessive input costs, and environmental degradation due to overuse of chemicals. Language barriers, low digital literacy, and absence of localized tools further limit their access to modern agri-tech resources.

Impact / Why this problem needs to be solved

Helping small farmers make informed decisions can significantly increase productivity, reduce costs, and improve livelihoods. It also contributes to sustainable farming practices, food security, and environmental conservation. A smart advisory solution can empower farmers with scientific insights in their native language and reduce dependency on unreliable third-party advice.

Expected Outcomes

• A multilingual, AI-based mobile app or chatbot that provides real-time, location-specific crop advisory.
• Soil health recommendations and fertilizer guidance.
• Weather-based alerts and predictive insights.
• Pest/disease detection via image uploads.
• Market price tracking.
• Voice support for low-literate users.
• Feedback and usage data collection for continuous improvement.

Relevant Stakeholders / Beneficiaries

• Small and marginal farmers
• Agricultural extension officers
• Government agriculture departments
• NGOs and cooperatives
• Agri-tech startups

Supporting Data

• 86% of Indian farmers are small or marginal (NABARD Report, 2022).
• Studies show ICT-based advisories can increase crop yield by 20–30%.

## Problem Creater's Organization
Government of Punjab

## Theme
Agriculture, FoodTech & Rural Development

## Proposed Solution
We propose SmartCropAid - a platform set up on rules and machinery.

Detailed Explanation

Farmers give background information on how big their patch 1 is, what kind of planting and what kind of ground types there are. Employing weather APIs, soil maps and agronomic principles, the system customizes instructions. AI models decide yield potential, pest and disease risk levels, and need for irrigation. Advice goes out via a mobile app, SMS, or IVR in the farmer's local language. A feedback mechanism makes it possible for farmers to report whether an advice has been helpful. This makes the system more accurate over time.

How It Addresses the Problem

Under SmartCropAid, farmers no longer have to worry about relying on hearsay from shopkeepers outside the bank. They obtain tailor-made action points local to themselves. Furthermore, it accommodates non-smartphone users by way of alternative modes of communication

## Technical Approach
Farmer registers via SMS/App → system stores profile.

Backend fetches weather + soil data for location.

Rule engine + ML generate advisory (crop choice, irrigation, fertilizer, alerts).

Notification layer sends advice → Farmer receives SMS/App message/IVR call.

Farmer feedback (e.g., reply code “1” for useful, “0” for not useful).

Feedback updates dataset → ML retrains gradually.

## Feasibility and Viability
Feasibility: Mobile penetration in rural India is >70%. Most farmers can access SMS or voice services. Initial pilot can run with district-level soil data and public weather APIs.

Viability: Once scaled, state governments, NGOs, and cooperatives can sponsor rollouts. Cost per farmer is minimal once platform is built.



## Impact and Benefits
Balanced fertilizer use prevents soil degradation.
Reduced chemical pesticide reliance protects ecosystems.
Water conservation via optimized irrigation scheduling.




## Research and References
NABARD All India Rural Financial Inclusion Survey (2022).

FAO Digital Agriculture Transformation report (2021).

ICAR crop calendar and soil health card datasets.

OpenWeatherMap and IMD weather APIs for real-time weather data.

Academic papers on ICT-based farmer advisory (Elsevier, Springer).
