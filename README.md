# MIT Capstone Research Ideas

## Table of Contents

1.  [Intelligent Inventory Management and Demand Forecasting for
    Philippine
    MSMEs](#1-intelligent-inventory-management-and-demand-forecasting-for-philippine-msmes)
2.  [Offline-First Mobile Learning and Adaptive Assessment
    System](#2-offline-first-mobile-learning-and-adaptive-assessment-system)
3.  [Mobile Document Scanner with Intelligent Information
    Extraction](#3-mobile-document-scanner-with-intelligent-information-extraction)
4.  [Offline-Capable Mobile Emergency Reporting and Disaster Information
    System](#4-offline-capable-mobile-emergency-reporting-and-disaster-information-system)
5.  [Explainable AI-Based Academic Risk Prediction and Intervention
    Support](#5-explainable-ai-based-academic-risk-prediction-and-intervention-support)
6.  [Intelligent Table of Specifications and Assessment Quality
    Analytics](#6-intelligent-table-of-specifications-and-assessment-quality-analytics)
7.  [Offline-First Adaptive Learning System for Programming
    Education](#7-offline-first-adaptive-learning-system-for-programming-education)
8.  [AI-Assisted Competency Mapping and Curriculum Gap
    Analysis](#8-ai-assisted-competency-mapping-and-curriculum-gap-analysis)

------------------------------------------------------------------------

------------------------------------------------------------------------

## 1. Intelligent Inventory Management and Demand Forecasting for Philippine MSMEs

*Best overall recommendation*

### Proposed Research Title

**Design and Evaluation of a Machine Learning-Based Inventory
Forecasting and Replenishment Decision Support System for Micro and
Small Retail Enterprises in Tarlac City**

### Problem Statement

Many small retail businesses rely on manual inventory records or
spreadsheets. This may result in stockouts, overstocking, expired
merchandise, and inaccurate purchasing decisions.

Although digital inventory systems exist, small retailers may lack
affordable tools that combine sales forecasting with practical
purchasing recommendations.

### Research Gap To Investigate

Existing inventory forecasting studies often evaluate predictive
accuracy, but your research could investigate whether a lightweight,
locally deployed forecasting system improves inventory decisions in
small Philippine retailers with limited and irregular sales records.

The research contribution would be the evaluation of forecasting
accuracy and operational benefits, not merely the creation of an
inventory application.

### Research Objectives

1.  Analyze historical sales and inventory patterns of selected MSMEs.
2.  Develop forecasting models using Random Forest, XGBoost, and
    statistical baseline methods.
3.  Design a replenishment recommendation algorithm based on predicted
    demand, supplier lead time, and safety stock.
4.  Develop an interactive inventory and sales dashboard.
5.  Evaluate forecast accuracy, stockout frequency, inventory holding
    costs, and system usability.

### Methodology

**Research design:** Design Science Research with quantitative
comparative evaluation.

**Data collection:** Obtain 6–12 months of sales and inventory records
from participating retail businesses, where available.

**Development:** Train forecasting models and integrate the
best-performing model into a web-based decision-support system.

**Evaluation:** Use time-based validation and compare model forecasts
with simple baselines such as seasonal naïve forecasting. Evaluate
replenishment recommendations through historical simulation and, if
feasible, a small pilot implementation.

### Technology Stack

Python, pandas, scikit-learn, XGBoost, PHP, MariaDB, Chart.js, HTML,
CSS, JavaScript, and XAMPP.

**Estimated cost:** ₱0–₱1,500

**Potential respondents:** Sari-sari store operators, minimart owners,
school canteen operators, and small retail businesses.

------------------------------------------------------------------------

## 2. Offline-First Mobile Learning and Adaptive Assessment System

*Best overall recommendation*

### Proposed Research Title

**Design and Evaluation of an Offline-First Adaptive Mobile Learning and
Assessment Framework for Higher Education Students in Low-Connectivity
Environments**

### Problem Statement

Students in areas with unreliable internet connectivity may experience
difficulty accessing learning materials, answering assessments, and
synchronizing academic progress.

Although existing learning management systems offer mobile access, not
all are designed to provide adaptive assessments while operating
primarily offline.

### Research Gap To Investigate

The proposed contribution is a framework that combines offline-first
synchronization, adaptive question selection, and conflict resolution
for students who experience intermittent connectivity.

Rather than claiming that offline mobile learning is new, the research
would evaluate whether the combination improves assessment continuity
and learning efficiency under realistic network interruptions.

### Research Objectives

1.  Develop a mobile application that stores learning materials and
    assessments locally.
2.  Implement adaptive question selection based on learner performance.
3.  Develop a synchronization mechanism that handles interrupted
    connections and duplicate submissions.
4.  Evaluate learning performance, synchronization reliability, and
    application usability.
5.  Compare the proposed framework against a conventional nonadaptive
    assessment approach.

### Methodology

**Research design:** Design Science Research with quasi-experimental
evaluation.

**Participants:** Higher education students and instructors, subject to
institutional approval.

**Development:** Implement local data storage, adaptive assessment
logic, and a PHP-based synchronization API.

**Testing:** Simulate unstable internet conditions and compare offline
and online performance.

**Evaluation metrics:** Assessment completion rate, synchronization
success rate, duplicate record frequency, response time, and learning
gains.

### Technology Stack

| Component          | Technology                                            |
|--------------------|-------------------------------------------------------|
| Mobile frontend    | Flutter / Dart                                        |
| Local database     | SQLite                                                |
| Backend            | Classic PHP                                           |
| Server database    | MariaDB                                               |
| Local server       | XAMPP                                                 |
| Adaptive algorithm | Item Response Theory or rule-based adaptive selection |
| Testing            | Android Emulator, existing Android phone              |

**Estimated budget:** ₱0–₱1,500

------------------------------------------------------------------------

## 3. Mobile Document Scanner with Intelligent Information Extraction

### Proposed Research Title

**Development and Performance Evaluation of an On-Device Intelligent
Document Scanning and Information Extraction Framework for Philippine
Educational and Administrative Forms**

### Problem Statement

Schools and small organizations frequently process printed forms,
receipts, and administrative documents.

Manual encoding is time-consuming and susceptible to transcription
errors. Cloud-based document extraction may also raise privacy and
connectivity concerns.

### Research Gap To Investigate

A defensible contribution would be evaluating the accuracy and
efficiency of offline, on-device information extraction for selected
Philippine document formats, particularly under poor lighting,
low-quality cameras, and mixed Filipino-English text.

### Research Objectives

1.  Develop a mobile document scanner with automatic edge detection and
    perspective correction.
2.  Implement offline optical character recognition.
3.  Extract structured fields from selected document templates.
4.  Compare extraction accuracy under different lighting and document
    conditions.
5.  Evaluate processing speed, resource consumption, and user usability.

### Methodology

**Research design:** Experimental software development and comparative
performance evaluation.

**Dataset:** Authorized or synthetic samples of school forms,
application documents, and receipts.

**Development:** Implement image preprocessing, OCR, field extraction,
and local storage.

**Evaluation:** Compare raw OCR against OCR with preprocessing using
character error rate, word error rate, field extraction F1-score, and
processing time.

**Scope limitation:** Restrict the study to a manageable set of document
templates rather than claiming support for all Philippine forms.

### Technology Stack

Flutter or Kotlin, OpenCV, Google ML Kit on-device text recognition,
SQLite, and Python for experimental evaluation.

**Estimated budget:** ₱0–₱2,000

This is a technically strong project because it combines mobile
development, computer vision, OCR, and measurable performance
benchmarking.

------------------------------------------------------------------------

## 4. Offline-Capable Mobile Emergency Reporting and Disaster Information System

### Proposed Research Title

**Design and Evaluation of an Offline-Capable Geospatial Mobile Incident
Reporting Framework for Community Disaster Preparedness in the
Philippines**

### Problem Statement

During floods, typhoons, and other emergencies, unstable communication
networks can delay the reporting of incidents and damage.

Community members may be unable to submit reports when internet
connectivity is unavailable.

### Research Gap To Investigate

The research would evaluate whether an offline-capable mobile reporting
framework can preserve incident information, prevent duplicate reports,
and reliably synchronize submissions when connectivity returns.

It could also examine the accuracy of incident location recording and
the usability of the application during simulated emergency conditions.

### Research Objectives

1.  Develop an Android application for recording incidents and their
    locations.
2.  Implement offline storage of reports, photographs, and coordinates.
3.  Develop reliable synchronization and duplicate-report detection.
4.  Create a geospatial dashboard for reviewing submitted reports.
5.  Evaluate synchronization performance, reporting accuracy, and
    usability.

### Methodology

**Research design:** Design Science Research with scenario-based
experimental testing.

**Participants:** Community volunteers or authorized disaster-response
personnel.

**Development:** Build offline reporting, GPS integration, and server
synchronization.

**Evaluation:** Test simulated connectivity interruptions, duplicate
submissions, and delayed synchronization.

**Safety limitation:** This must be evaluated as a prototype, not as a
replacement for official emergency hotlines or government warning
systems. Reports collected during testing should be clearly marked as
simulated.

### Technology Stack

Flutter, SQLite, PHP, MariaDB, OpenStreetMap-based mapping, and Leaflet
for the administrator dashboard.

**Estimated budget:** ₱0–₱2,500

Offline map tiles may require additional storage and licensing
considerations. A limited geographic study area would keep the project
manageable.

------------------------------------------------------------------------

## 5. Explainable AI-Based Academic Risk Prediction and Intervention Support

*Best for predictive analytics research*

### Proposed Research Title

**Development and Evaluation of an Explainable Machine Learning-Based
Academic Early Warning and Intervention Decision Support System for
Higher Education Students**

### Problem Statement

Academic difficulties are often identified only after students receive
low examination scores or failing grades. Manual monitoring of
attendance, quizzes, and academic performance can delay the
identification of students who need additional support.

Predictive models can identify students at risk, but educators may find
their predictions difficult to interpret or translate into appropriate
interventions.

### Research Gap To Investigate

Machine learning for student risk prediction is already well
established. A more defensible research contribution would examine
whether interpretable predictions based on limited, locally available
student data can improve early identification and instructor
decision-making in Philippine higher education.

### Research Objectives

1.  Develop and compare Logistic Regression, Random Forest, and XGBoost
    models.
2.  Identify academic factors associated with students' risk of failing.
3.  Integrate SHAP explanations into an academic monitoring dashboard.
4.  Evaluate predictive performance using recall, F1-score, PR-AUC, and
    calibration.
5.  Assess the usefulness of the system for instructor decision-making.

### Methodology

**Research design:** Design Science Research with quantitative model
evaluation.

**Data collection:** Obtain anonymized historical academic records with
institutional approval.

**Model development:** Train models on earlier academic terms and
evaluate on later terms to reduce data leakage.

**System evaluation:** Conduct usability testing with instructors and
compare risk identification against existing monitoring practices.

### Technology Stack

Python, scikit-learn, XGBoost, SHAP, PHP, MariaDB, Chart.js, and XAMPP.

**Estimated budget:** ₱0–₱1,500.

**Major feasibility concern:** Sufficient historical student data must
be available, and the model should not use information that would only
become known after the prediction date.

------------------------------------------------------------------------

## 6. Intelligent Table of Specifications and Assessment Quality Analytics

*My strongest recommendation for you*

### Proposed Research Title

**Design and Evaluation of an Intelligent Table of Specifications
Alignment and Examination Quality Analytics Framework Using Natural
Language Processing and Constraint Optimization**

### Problem Statement

Teachers prepare examination questions based on learning competencies,
cognitive levels, and a Table of Specifications (TOS). However, manually
checking whether questions match competencies and follow the required
item distribution can be time-consuming.

Questions may also be incorrectly classified according to cognitive
level or difficulty, resulting in assessment misalignment.

### Research Gap To Investigate

Automated question classification and test blueprinting are existing
research areas. Your proposed contribution could investigate whether
semantic competency matching combined with constraint optimization
improves examination alignment and reduces preparation time compared
with manual TOS checking.

A further contribution would be distinguishing intended difficulty from
empirically observed item difficulty.

### Research Objectives

1.  Develop an NLP model to recommend competency alignment for
    examination questions.
2.  Implement a cognitive-level classification mechanism based on
    Bloom's Revised Taxonomy.
3.  Develop an optimization algorithm that selects questions according
    to TOS requirements.
4.  Integrate classical item analysis using student examination results.
5.  Evaluate alignment accuracy, blueprint compliance, teacher review
    time, and usability.

### Methodology

**Research design:** Design Science Research with comparative
experimental evaluation.

**Data collection:** Gather authorized TOS documents, learning
competencies, examination questions, and anonymized student responses.

**Development:** Implement semantic matching, cognitive-level
classification, and a constraint-based examination assembly algorithm.

**Validation:** Ask qualified instructors to independently classify a
sample of questions and establish a reviewed reference set.

**Evaluation:** Compare AI-assisted and manual examination preparation
using alignment precision, macro F1-score, exact blueprint compliance,
and task completion time.

### Technology Stack

| Component     | Free technology               |
|---------------|-------------------------------|
| Frontend      | HTML, CSS, JavaScript         |
| Backend       | Classic PHP                   |
| Database      | MariaDB                       |
| NLP           | Python, Sentence Transformers |
| Optimization  | Google OR-Tools               |
| Item analysis | pandas, NumPy                 |
| Visualization | Chart.js                      |
| Local server  | XAMPP                         |

**Estimated budget:** ₱0–₱1,500.

**Why this is promising:** It has a clear research component, can be
developed locally, and could directly support instructors who prepare
examinations using competency-based TOS documents.

------------------------------------------------------------------------

## 7. Offline-First Adaptive Learning System for Programming Education

### Proposed Research Title

**Development and Evaluation of an Offline-First Adaptive Learning
Framework for Improving Foundational Programming Competencies Among
Philippine Higher Education Students**

### Problem Statement

Students learning programming often have different levels of
understanding and require different amounts of practice.

Conventional learning platforms may provide identical activities to all
students regardless of their performance. In addition, intermittent
internet connectivity can disrupt access to lessons and exercises.

### Research Gap To Investigate

Adaptive learning and offline educational applications are not new. The
proposed study could examine the combined effectiveness of mastery-based
activity sequencing and reliable offline synchronization for
introductory programming education.

### Research Objectives

1.  Develop an offline-first learning application for introductory
    programming.
2.  Implement an adaptive algorithm that recommends exercises based on
    demonstrated competency.
3.  Design a synchronization mechanism that handles interrupted
    connections.
4.  Evaluate programming competency gains through pretests and
    posttests.
5.  Measure application usability, synchronization reliability, and
    learner engagement.

### Methodology

**Research design:** Quasi-experimental study combined with Design
Science Research.

**Participants:** Students enrolled in introductory programming courses.

**Development:** Build competency-based lessons and exercises with a
local database and a synchronization API.

**Evaluation:** Compare adaptive learning with a fixed sequence of
programming exercises, preferably using comparable student groups.

**Metrics:** Learning gain, assessment completion rate, synchronization
success, response time, and usability.

### Technology Stack

Flutter or a Progressive Web App, JavaScript, SQLite or IndexedDB, PHP,
MariaDB, and XAMPP.

**Estimated budget:** ₱0–₱2,000.

**Scope recommendation:** Limit the first implementation to introductory
C++ concepts such as conditionals, loops, functions, and arrays. This
would keep development and evaluation manageable.

------------------------------------------------------------------------

## 8. AI-Assisted Competency Mapping and Curriculum Gap Analysis

### Proposed Research Title

**Design and Evaluation of a Semantic Competency Mapping and Curriculum
Gap Detection Framework for Philippine Technical-Vocational and Higher
Education Programs**

### Problem Statement

Curriculum development requires aligning learning outcomes,
instructional activities, and assessment methods.

Manually reviewing these relationships can be difficult, especially when
programs contain numerous competencies and assessment requirements.

### Research Gap To Investigate

The study could evaluate whether lightweight semantic language models
improve competency mapping accuracy and consistency when applied to
Philippine curriculum documents.

The research should also examine whether AI recommendations can identify
missing or weakly represented competencies without incorrectly treating
semantic similarity as proof of curriculum compliance.

### Research Objectives

1.  Develop a framework for extracting competencies from curriculum
    documents.
2.  Implement semantic similarity models to recommend mappings between
    competencies, lessons, and assessments.
3.  Detect potentially unaddressed competencies.
4.  Compare semantic matching against keyword-based approaches.
5.  Evaluate mapping accuracy and expert acceptance.

### Methodology

**Research design:** Design Science Research with expert validation.

**Data collection:** Obtain authorized curriculum documents, competency
standards, and assessment instruments.

**Development:** Extract text, generate semantic embeddings, and build a
competency relationship matrix.

**Validation:** Ask curriculum specialists to review and label a
representative set of competency mappings.

**Evaluation:** Precision, recall, F1-score, expert agreement, and time
required to complete mapping tasks.

### Technology Stack

Python, Sentence Transformers, scikit-learn, FastAPI, PHP, MariaDB, and
Chart.js.

**Estimated budget:** ₱0–₱2,000.

**Potential application:** TESDA competency-based curricula,
housekeeping training, and higher education course-outcome mapping.
