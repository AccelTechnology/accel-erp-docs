### User Manual for Project Detail Page

#### Overview
The Project Detail Page provides a comprehensive view of a project's details, including general information, planning, ownership, financials, authorization, and associated entities like work orders, resources, materials, documents, and technical particulars.

#### Page Structure

1. **Page Title**: Displays the title "Project".
2. **Breadcrumbs**: Navigation links to the Project List and parent project details.
3. **Tabs**: Different sections of the project details are organized into tabs.

#### Tabs and Fields

1. **Details Tab**:
    - **General Section**:
        - **Code**: Project code (string).
        - **Status**: Project status (enum).
        - **Name**: Project name (string).
        - **Description**: Project description (string).
        - **Project Type**: Type of the project (entity).
        - **Parent Project**: Parent project (entity).

    - **Planning Information Section**:
        - **Planned Start Date**: Planned start date (date).
        - **Planned End Date**: Planned end date (date).
        - **Actual Start Date**: Actual start date (date).
        - **Actual End Date**: Actual end date (date).

    - **Ownership Section**:
        - **Project Owner**: Owner of the project (entity).
        - **Project Manager**: Manager of the project (entity).
        - **Project Department**: Department responsible for the project (entity).

    - **Financials Section**:
        - **Financial Account**: Financial account associated with the project (entity).

    - **Authorization Section**:
        - **Authorized By**: Person who authorized the project (entity).
        - **Authorized Date**: Date of authorization (date).

2. **Project Hierarchy Tab**:
    - Displays a grid of child projects with columns for code, name, status, type, planned start date, planned end date, start date, end date, and project manager.

3. **Work Order Tab**:
    - Displays a grid of work orders with columns for code, priority, name, team, status, planned start date, due date, start date, and end date.

4. **Resource Planning Tab**:
    - Displays a grid of project resources with columns for qualification, costing method, rate amount, fixed amount, crew size, and required hours.

5. **Material Planning Tab**:
    - Displays a grid of project materials with columns for product code, product name, costing method, rate amount, fixed amount, quantity, and unit.

6. **Documents Tab**:
    - Displays a grid of project documents with columns for code, document group, description, type, status, version, author, and last modified date.

7. **Technical Particular Tab**:
    - Displays a grid of technical particulars with columns for code, name, status, expected value, and proposed value.

8. **Project Summary Tab**:
    - Displays a Gantt chart of work orders showing the project timeline.

9. **Discussion Tab**:
    - Provides a section for project-related discussions.

#### Actions

- **Item Detail Route**: Navigate to the detail view of an item by clicking on its link.
- **New Item Route**: Create a new item with pre-filled parameters based on the current project context.
- **Default Sort**: Columns are sorted by default based on specified fields.

#### Usage Tips

- Use the breadcrumbs for easy navigation between related projects.
- Utilize the tabs to quickly access different aspects of the project.
- Pay attention to the status badges for a quick overview of the project's progress and issues.
- Use the Gantt chart in the Project Summary tab to visualize the project timeline and dependencies.

This manual provides a high-level overview of the Project Detail Page and its functionalities. For more detailed instructions, refer to the specific sections and fields as described.