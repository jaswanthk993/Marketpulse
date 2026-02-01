# Requirements – AI Copilot for Small Businesses (BizPilot AI)

## 1. Overview
BizPilot AI is an AI-powered copilot designed to help small business owners make better day-to-day decisions using their existing sales and inventory data.  
The system provides natural language insights, inventory recommendations, sales analysis, and proactive alerts.

---

## 2. Business Requirements

- BR-1: The system must improve decision-making for inventory, sales, and profit tracking.
- BR-2: The system must reduce manual analysis and reporting effort.
- BR-3: The system must provide actionable recommendations, not just dashboards.
- BR-4: The system must be usable by non-technical users.

---

## 3. User Requirements

- UR-1: Users must be able to ask questions in plain English.
- UR-2: Users must receive clear, concise answers with explanations.
- UR-3: Users must receive alerts before operational issues occur.
- UR-4: Users must be able to upload data without technical setup.

---

## 4. Functional Requirements

### 4.1 Data Ingestion
- FR-1: The system must support CSV uploads for sales, inventory, and purchase data.
- FR-2: The system must validate uploaded data and report errors clearly.
- FR-3: The system must automatically map common column names.

### 4.2 AI Copilot
- FR-4: The system must answer inventory, sales, and profit-related questions.
- FR-5: The system must convert natural language queries into data queries.
- FR-6: The system must summarize insights in simple language.

### 4.3 Inventory Intelligence
- FR-7: The system must predict stock-out risk.
- FR-8: The system must suggest reorder quantities.
- FR-9: The system must identify slow-moving and dead stock.

### 4.4 Sales & Profit Analysis
- FR-10: The system must calculate product-level profit.
- FR-11: The system must analyze sales trends over time.
- FR-12: The system must identify declining and high-performing products.

### 4.5 Alerts & Notifications
- FR-13: The system must generate low-stock alerts.
- FR-14: The system must generate sales drop alerts.
- FR-15: The system must generate dead-stock alerts.

---

## 5. Non-Functional Requirements

### 5.1 Performance
- NFR-1: Chat responses must be returned within 3 seconds.
- NFR-2: Data processing must complete within 30 seconds.

### 5.2 Scalability
- NFR-3: The system must support at least 1,000 active users.
- NFR-4: Backend services must be stateless.

### 5.3 Security & Privacy
- NFR-5: User data must be isolated and access-controlled.
- NFR-6: Data must be encrypted in transit and at rest.
- NFR-7: Secure authentication is required.

### 5.4 Reliability
- NFR-8: The system must handle invalid or missing data gracefully.
- NFR-9: The system must provide fallback responses if AI services fail.

---

## 6. AI / ML Requirements

- AIR-1: The system must use time-series forecasting for demand prediction.
- AIR-2: The system must use rule-based logic for alerts in MVP.
- AIR-3: The system must use an LLM for natural language understanding.
- AIR-4: The system must provide explainable AI outputs.

---

## 7. Data Requirements

- DR-1: A minimum of 30 days of historical sales data is required for forecasting.
- DR-2: Missing or inconsistent data must be flagged.
- DR-3: All data must be scoped to individual users.

---

## 8. UX Requirements

- UXR-1: A chat-first interface must be the primary interaction model.
- UXR-2: Insights must be understandable within 10 seconds.
- UXR-3: Visualizations must be simple and minimal.

---

## 9. Constraints

- CSV-based data ingestion only (MVP).
- English language only.
- No automated ordering or payments.
- No accounting or tax filing features.

---

## 10. Acceptance Criteria

- Users can upload data and query insights via the AI Copilot.
- The system provides accurate, explainable recommendations.
- Alerts trigger correctly based on defined thresholds.
- The application remains stable during demo usage.
