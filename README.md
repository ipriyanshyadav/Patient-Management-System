# Patient-Management-System

A modern REST API to manage patient records, built with FastAPI and Pydantic. This system enables you to create, view, update, delete, and sort patient information, while automatically computing BMI and health verdicts. Suitable for clinics, research, or learning RESTful API design.

**Features**

RESTful API with FastAPI — Quick, async endpoints for all CRUD operations.
Pydantic Models — Strong schema validation for patient input and updates.
Computed Fields — BMI and health verdict (“Underweight,” “Normal,” “Obese”) calculated on-the-fly.
Sort Functionality — View or sort patients by height, weight, or BMI (ascending/descending).
In-Memory Data — Easy editing and viewing through a local JSON “database”.
Extensible Structure — Simple to extend for new features or integrations.
