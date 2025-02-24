# AutoGuided Onboarding WebApp for Carbon Footprint Reduction

## Background

The AutoGuided Onboarding webApp (AGO) aims to address the pressing issue of carbon footprint reduction through innovative technology. By leveraging autonomous small satellites (smallsats) for earth observation, this webApp provides users with personalized insights and recommendations to help them reduce their carbon footprint. The goal is to empower individuals and organizations to take actionable steps towards a more sustainable future.
![Auto smallsat network topology](https://github.com/aimtyaem/EOInfo/blob/a71ee89bf3f7443bb7766dca35ce432feffd1bfd/1751033024.jpg)


## Repository Structure

```
autoguided-webapp/  
├── frontend/onboarding.Yaml # Output 
│   ├── pages/onboarding.Html /Dashboard.html # WebApp  
│   └── components/Dashboard.json  
├── backend/             # DevOps  
│   ├── routes/Sat_data.ipynb  
│   └── ml/carbon_model.ipynb
|   └── H2Ogpt/Onboarding_Dashbiard_AutoGuidedChatbot
├── AutoSmallSat_Datasets/ # SmallSat integration  
│   ├── aws_ground_station.ipynb  
│   └── imagery_processing.ipynb  
├── Output/  # Reports  
└── Branches files/  # User/developer guides  
```

## AutoGuided Structure

This project includes the following components:
1. [**Wireframe Design**](https://github.com/aimtyaem/AGO/blob/b9f9b99a274edd9a972ba92275929249777fbd43/CFPwireframe.md)
2. [**Prototype**](https://github.com/aimtyaem/EOInfo/blob/08afb04bd43a655a6df00f61d4439ada01c1e1b8/CFP%20prototype%20plan.pdf)
3. [**Mockup Design**](https://github.com/aimtyaem/AGO/blob/74d35465edc166cfb2dbcbe356e0626d3de97e5b/README.md#mockup-design)
4. [**Getting started**](https://github.com/aimtyaem/AGO/blob/main/Setup.MD)

## Wireframe Design

### Homepage
```
+-----------------------------+
|       Homepage              |
|-----------------------------|
|  Headline                   |
|  Introduction               |
|  [CTA Button]               |
+-----------------------------+
```

### Onboarding Flow
```
+-----------------------------+
|   Onboarding Flow           |
|-----------------------------|
|  Step 1: Introduction       |
|  Step 2: Features Overview  |
|  Step 3: Set Up Profile     |
|  [Start Using the App]      |
+-----------------------------+
```

### Dashboard
```
+-----------------------------+
|        Dashboard            |
|-----------------------------|
|  Carbon Footprint Overview  |
|  [Charts & Graphs]          |
|  Recommendations            |
+-----------------------------+
```

### User Profile
```
+-----------------------------+
|      User Profile           |
|-----------------------------|
|  Profile Info               |
|  Settings & Preferences     |
|  Social Media Connections   |
+-----------------------------+
```

### Resource Center
```
+-----------------------------+
|     Resource Center         |
|-----------------------------|
|  Articles & Videos          |
|  [Search & Filter]          |
+-----------------------------+
```

### Community
```
+-----------------------------+
|        Community            |
|-----------------------------|
|  Forums & Discussions       |
|  User Groups & Challenges   |
+-----------------------------+
```

## Prototype

1.Working on turning our prototype into the [MVP!](https://github.com/aimtyaem/EOInfo/blob/b9f9b99a274edd9a972ba92275929249777fbd43/Turning%20prototype%20into%20MVP.pdf).

2.The interactive mockup can be found [here](https://CFP0.blogspot.com). It includes detailed information and user flows to illustrate the user experience and interactions.

## Mockup Design

### Homepage Mockup
![Homepage Mockup](https://github.com/aimtyaem/EOInfo/blob/4871c5b7a1382d357cbd3966987cd0fe2303429d/chrome_screenshot_13%20Feb%202025%2017_48_43%20EET.png)

### Onboarding Flow Mockup
![Onboarding Flow Mockup](https://github.com/aimtyaem/EOInfo/blob/ac2963b42c25d13a57d874827f32249cc84dd5a1/chrome_screenshot_13%20Feb%202025%2017_51_23%20EET.png)

### Dashboard Mockup
![Dashboard Mockup](https://github.com/aimtyaem/EOInfo/blob/ac2963b42c25d13a57d874827f32249cc84dd5a1/chrome_screenshot_13%20Feb%202025%2017_50_27%20EET.png)

### User Profile Mockup
![User Profile Mockup](https://github.com/aimtyaem/EOInfo/blob/ac2963b42c25d13a57d874827f32249cc84dd5a1/chrome_screenshot_13%20Feb%202025%2017_51_57%20EET.png)

### Resource Center Mockup
![Resource Center Mockup](https://github.com/aimtyaem/EOInfo/blob/ac2963b42c25d13a57d874827f32249cc84dd5a1/chrome_screenshot_13%20Feb%202025%2017_52_31%20EET.png)

### Community Mockup
![Community Mockup](https://github.com/aimtyaem/EOInfo/blob/10959760b8be18be7f683c43a5bdf58b40f90eb8/chrome_screenshot_13%20Feb%202025%2017_49_48%20EET.png)

## Development Requirements
To contribute to the development of the "CFP Prototype Plan.pdf" project, you will need the following:

- A development environment with the latest version of Python installed.
- The following Python packages:
  - numpy
  - scipy
  - matplotlib
  - pandas
  - scikit-learn
  - tensorflow
  - keras
- A git client.

## Getting Started: Development installations guidelines 

To get started with the development of this project, follow the steps below:
1. Clone the repository.
2. Install necessary dependencies.
3. Follow the wireframe and mockup designs to develop the frontend and backend components.
4. Integrate AI models and data processing modules.
5. Conduct user testing and gather feedback for improvements. 

## Contribution Guidelines:

To ensure a smooth and consistent contribution process, please adhere to the following guidelines:

- **Code contributions:**
  - Follow the project's coding standards and conventions.
  - Write clear and concise commit messages that describe the changes made.
  - Include unit tests for new or modified code.
- **Documentation updates:**
  - Use clear and concise language that is easy to understand.
  - Provide sufficient context and examples to help users understand the concepts being explained.
  - Follow the project's documentation style guide.
- **Issue reporting:**
  - Provide a clear and detailed description of the issue, including steps to reproduce it.
  - Include any relevant error messages or logs.
  - Assign the appropriate label to the issue (e.g., "bug," "feature request," etc.).
- **Feature requests:**
  - Describe the proposed feature in detail, explaining its purpose and benefits.
  - Provide any relevant mockups or designs to illustrate the feature.
  - Discuss the potential impact of the feature on the project's architecture and implementation.

**4. Code of Conduct**
We expect all contributors to adhere to our code of conduct, which promotes a respectful and inclusive environment. Please refrain from personal attacks, offensive language, or any form of harassment.

**5. Contact**
If you have any questions or need assistance with contributing, please contact [Project Contact Name] at [Project Contact Email].

We appreciate your contributions and look forward to collaborating with you!
[![Watch the video](https://img.youtube.com/vi/NCboNufaOsg/0.jpg)](https://www.youtube.com/watch?v=NCboNufaOsg)

### License
The AGO project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
For more information, please contact aimt16@hotmail.com. 

We hope this project inspires and empowers users to contribute to a sustainable future by reducing their carbon footprints with the help of advanced technology.
