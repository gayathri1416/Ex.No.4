# Ex.No.4-EXP 4 Generate the Prompt and evaluate that for following prompt patterns - Zero-shot Prompting.•	Few-shot Prompting - Chain of Thought -	Persona Pattern - Reverse Prompting - Graph Prompting - Active Prompting
### DATE:   20.11.2026                                                                         
### REGISTER NUMBER : 212225040092
### Aim: To write the prompt for the following prompt types and compare that with different AI tools and evaluate that using any one evaluation method (Ex. Rubrics). Zero-shot Prompting.•	Few-shot Prompting - Chain of Thought -	Persona Pattern - Reverse Prompting - Graph Prompting - Active Prompting 

### Explanation - Any one use case from Unit 5 and write the prompt for that with the unit 2 Prompt types given above.

Procedure:
1.	Define the Scenario and Use Case:
Scenario:
The manufacturing industry is looking to reduce manual monitoring and increase efficiency through automation. The system will utilize IoT devices and embedded controllers to automate equipment, monitor performance, and enable predictive maintenance. The goal is to streamline the production process, minimize downtime, and enhance energy efficiency.
Target Audience:
Manufacturing companies, specifically in sectors like automotive, electronics, and food processing, where automation can significantly improve productivity.

Main Objectives:

•	Improve production efficiency by 30%.
•	Minimize machinery downtime with predictive maintenance.
•	Enable real-time monitoring and remote control of manufacturing systems.
•	Reduce energy consumption by optimizing processes.
 
2.	Identify Prompt Patterns for Each Design Aspect:
Idea Generation Prompts:

Comparative Analysis Prompt
Definition: Asking for a comparison between two or more concepts, often highlighting similarities and differences.
•	"Compare and contrast deep learning and machine learning."
•	"How do renewable and non-renewable energy sources differ?"

Experiential Perspective Prompt:
> 	“As a software engineer, what are the benefits of using cloud computing in your projects?”
>  “From a student’s perspective, describe the challenges of online learning.”

Everyday Functioning Prompts:
*	  “Describe the role of machine learning in everyday apps like YouTube or Netflix."
*	 	“How is encryption used in daily life when sending WhatsApp messages?”

Universal Prompt Structures:
^ 	“Explain [concept] in simple terms with an example.”
^  “Explain the process of [task] step by step.”

Prompt Size Limitations:
&  	“Translate this 5000-word essay into Tamil.”
→ Manageable chunks: “Translate the first 1000 words into Tamil, then continue.”
&  “Give me 50 examples of AI applications.”
→ Adjust for size: “Give me 10 AI applications at a time.”


**Selected Use Case: Smart Irrigation System**


The prompt patterns include:

1. Zero-shot Prompting
2. Few-shot Prompting
3. Chain of Thought Prompting
4. Persona Pattern
5. Reverse Prompting
6. Graph Prompting
7. Active Prompting

## 1. PROCEDURE

### Define the Scenario and Use Case

## Scenario: Smart Irrigation System

Traditional irrigation methods often waste water because farmers manually monitor soil conditions and operate water pumps. To overcome this problem, a Smart Irrigation System is developed using IoT sensors, embedded controllers, and automated water pumps.

The system continuously monitors soil moisture, temperature, and humidity. Based on the collected data, it automatically controls the water supply to crops.

**Target Audience:** Farmers, agricultural researchers, and agricultural technology companies.

### Main Objectives

- Reduce water wastage through automated irrigation.
- Monitor soil moisture in real time.
- Automatically control water pumps using IoT sensors.
- Improve crop growth and productivity.
- Reduce manual work and irrigation costs.
- Provide timely alerts to farmers.

## 2. IDENTIFY PROMPT PATTERNS FOR THE SCENARIO

### 2.1 Zero-shot Prompting

**Definition:** Zero-shot prompting provides an instruction to AI without giving any examples. The AI generates a response based on its existing knowledge.

**Prompt:**

"Explain how a Smart Irrigation System works using IoT sensors. Describe how soil moisture sensors, temperature sensors, and automatic water pumps help farmers save water and improve crop growth."

**Expected AI Output:**

A Smart Irrigation System uses IoT technology to monitor soil moisture and environmental conditions. When the soil becomes dry, the moisture sensor sends information to the controller. The controller activates the water pump automatically. When sufficient moisture is detected, the pump is switched off.

**Result:** AI generated a direct explanation of the smart irrigation system without requiring examples.

### 2.2 Few-shot Prompting

**Definition:** Few-shot prompting provides a small number of examples before asking AI to perform a similar task. It helps AI understand the expected response pattern.

**Prompt:**

"Observe the following examples and provide a suitable irrigation recommendation.

Example 1:\
Soil Moisture: 20% – Soil Condition: Dry – Action: Turn ON the water pump.

Example 2:\
Soil Moisture: 75% – Soil Condition: Wet – Action: Turn OFF the water pump.

Now analyze the following:

Soil Moisture: 30%

Provide the soil condition and recommended irrigation action in the same format."

**Expected AI Output:**

Soil Moisture: 30% – Soil Condition: Relatively Dry – Action: Turn ON the water pump (based on the illustrative 40% threshold).

**Result:** AI followed the given examples and generated an irrigation recommendation in the same format.

### 2.3 Chain of Thought Prompting

**Definition:** Chain of Thought prompting encourages AI to explain a problem-solving process through logical steps and provide a final answer.

**Prompt:**

"A smart irrigation system detects that soil moisture is 25%, while the required minimum moisture level is 40%.

Analyze the situation step by step. Identify the soil condition, explain the decision-making process of the controller, and determine whether the water pump should be switched ON or OFF. Provide a brief explanation of the final decision."

**Expected AI Output:**

1. The sensor measures the soil moisture as 25%.
2. The minimum required moisture level is 40%.
3. The measured moisture is below the required level.
4. The controller identifies that irrigation is needed.
5. The water pump is switched ON.

**Final Decision:** The water pump should be switched ON to provide sufficient water to the crops.

**Result:** AI generated a logical step-by-step explanation and identified the correct irrigation action.

### 2.4 Persona Pattern

**Definition:** Persona prompting assigns a specific role or identity to AI so that it generates responses from that professional perspective.

**Prompt:**

"Act as an agricultural IoT engineer. Design a Smart Irrigation System for a farm using soil moisture sensors, temperature sensors, a microcontroller, and an automatic water pump. Explain the working process, required components, and benefits of the system in simple terms."

**Expected AI Output:**

As an agricultural IoT engineer, I recommend the following components:

- Soil Moisture Sensor – Measures the water content in the soil.
- Temperature Sensor – Monitors environmental temperature.
- Microcontroller – Processes sensor information.
- Water Pump – Supplies water automatically.
- IoT Module – Sends information to a monitoring application.

**Working:** The sensors collect environmental data and send it to the microcontroller. Based on the moisture threshold, the controller activates or deactivates the water pump.

**Benefits:** Water conservation, reduced manual work, improved monitoring, and efficient irrigation.

**Result:** AI responded from the perspective of an agricultural IoT engineer and provided a technical solution.

### 2.5 Reverse Prompting

**Definition:** Reverse prompting involves asking AI to generate a suitable prompt or identify the information required to solve a given problem.

**Prompt:**

"I want to develop a Smart Irrigation System for a small agricultural farm. First, identify the important information and requirements needed to design the system. Then create a detailed prompt that can be used to generate a complete Smart Irrigation System design, including components, working process, IoT integration, and benefits."

**Expected AI Output:**

The AI identifies the following requirements:

- Farm size and crop type.
- Soil moisture requirements.
- Available water resources.
- Sensor and controller requirements.
- Internet connectivity.
- Water pump capacity.

**Generated Prompt:**

"Design an IoT-based Smart Irrigation System for a small farm using soil moisture sensors, a microcontroller, and an automatic water pump. Explain its architecture, working process, hardware components, software requirements, and advantages."

**Result:** AI identified the requirements and generated a suitable prompt for designing the irrigation system.

### 2.6 Graph Prompting

**Definition:** Graph prompting represents information through connected nodes and relationships. It helps AI understand how different components interact within a system.

**Prompt:**

"Represent the working of a Smart Irrigation System as a directed graph. Include soil moisture sensors, temperature sensors, microcontroller, water pump, water supply, and crops. Show the connections and explain how information and water flow between the components."

**Expected AI Output:**

**Graph Representation:**

Soil Moisture Sensor → Microcontroller → Water Pump → Crops

Temperature Sensor → Microcontroller

Water Supply → Water Pump

**Explanation:**

- Sensors collect soil and environmental information.
- The microcontroller processes the collected data.
- The water pump receives control signals.
- Water is supplied to crops when irrigation is required.

**Result:** AI represented the system using connected components and explained their relationships.

### 2.7 Active Prompting

**Definition:** Active prompting involves AI identifying missing information, asking relevant questions, and using the answers to generate a more accurate response.

**Prompt:**

"I want to develop a Smart Irrigation System for agricultural use. Before designing the system, ask me five important questions about farm size, crop type, soil moisture requirements, water availability, and budget. After receiving the answers, suggest a suitable irrigation system with the required components and working process."

**Expected AI Output:**

AI asks the following questions:

1. What is the size of the agricultural land?
2. Which crops are cultivated?
3. What is the required soil moisture level?
4. What is the available water source?
5. What is the estimated project budget?

After receiving the answers, AI generates a customized irrigation system design based on the provided requirements.

**Result:** AI collected additional information through questions and generated a more suitable solution based on the user's requirements.

## 3. EVALUATION METHOD – RUBRIC-BASED EVALUATION

The seven prompting techniques can be evaluated using the following criteria:

- Accuracy
- Relevance
- Completeness
- Clarity
- Practical Usefulness

**Scoring:**\
5 – Excellent, 4 – Very Good, 3 – Good, 2 – Satisfactory, 1 – Poor.

## 4. COMPARISON OF DIFFERENT AI TOOLS

The following table provides an illustrative comparison of ChatGPT, Google Gemini, and Microsoft Copilot based on the expected outputs.

| Prompt Type      | ChatGPT                 | Gemini                  | Copilot                      |
| ---------------- | ----------------------- | ----------------------- | ---------------------------- |
| Zero-shot        | Direct explanation      | Detailed explanation    | Concise explanation          |
| Few-shot         | Follows examples        | Identifies patterns     | Produces structured output   |
| Chain of Thought | Logical steps           | Stepwise explanation    | Structured reasoning summary |
| Persona          | Role-based response     | Contextual response     | Professional response        |
| Reverse          | Generates prompts       | Identifies requirements | Suggests prompt structure    |
| Graph            | Component relationships | Graph representation    | Structured connections       |
| Active           | Asks questions          | Collects requirements   | Provides guided questions    |



## 5. SAMPLE RUBRIC EVALUATION

| Prompt Type         | Score (Out of 5) |
| ------------------- | ---------------- |
| Zero-shot Prompting | 4                |
| Few-shot Prompting  | 5                |
| Chain of Thought    | 5                |
| Persona Pattern     | 4                |
| Reverse Prompting   | 4                |
| Graph Prompting     | 5                |
| Active Prompting    | 5                |

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/ce2d610a-7e11-4221-9904-347d5c7a04ab" />

## 6. CONCLUSION

The seven prompt engineering patterns were applied to the Smart Irrigation System scenario. Each technique generated different responses based on the instructions provided. Zero-shot prompting generated direct explanations, few-shot prompting followed examples, chain of thought provided logical steps, persona prompting generated professional responses, reverse prompting created suitable prompts, graph prompting represented system relationships, and active prompting collected additional requirements.

These techniques demonstrate how prompt engineering can be used in smart agriculture to design efficient irrigation systems, conserve water, and improve agricultural productivity.


# Result: 
The various types of Prompts are executed successfully with generated the report.
