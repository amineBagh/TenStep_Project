Welcome to the **Tenstep** project repository! This project focuses on leveraging **Graph Neural Networks (GNN)**, **Graph Convolutional Networks (GCN)**, **Llama models**, and **Retrieval-Augmented Generation (RAG)** to improve project management processes by building a robust knowledge graph system. Below are the key details and objectives of the project.

---

## Business Objectives (BO)

- **BO1: Improve Risk Mitigation and Identification:**  
  Develop models that can identify, assess, and mitigate risks in real time, ensuring better decision-making and risk management in projects.

- **BO2: Enhance Project Efficiency with Automated Knowledge Retrieval:**  
  Streamline project management workflows by automating the retrieval of knowledge from project archives, reducing time spent searching for past insights.

- **BO3: Improve Project Planning and Scheduling:**  
  Utilize advanced analytics to predict project timelines and optimize resource allocation for more efficient scheduling and planning.

---

## Data Science Objectives (DSO)

- **DS01: Build a Model to Extract and Categorize Risks**  
  Extract and categorize risks from project documents, providing actionable risk mitigation strategies based on **PMBOK** guidelines.

- **DS02: Use NLP and Communication Analytics**  
  Evaluate stakeholder sentiment using NLP to optimize communication strategies and engagement.

- **DS03: Automate Knowledge Retrieval**  
  Use machine learning and NLP to automate the retrieval of relevant knowledge from project archives, reducing time spent searching for past insights.

- **DS04: Apply Predictive Analytics for Scheduling Efficiency**  
  Apply predictive analytics to forecast project timelines, optimize resource allocation, and improve overall scheduling efficiency.

---

## Final Graph: Knowledge Graph Representation

Here, we show the knowledge graph built for the Tenstep system, which integrates relationships between tasks, resources, risks, and stakeholders. This graph helps visualize the project dependencies and facilitates decision-making across multiple levels of project management.

![Final Graph Image 1](/read_img/1.png)  
![Final Graph Image 2](/read_img/2.png)

*Explanation:*  
The knowledge graph represents the interconnections between various project components, such as tasks, stakeholders, and resources. These relationships help in risk mitigation, project planning, and optimization. By analyzing the graph, project managers can understand dependencies and make data-driven decisions to improve project outcomes.

---

## GNN (Graph Neural Networks)

**Fluctuating Loss:**  
- The model struggles with learning due to a small dataset, causing it to fail at generalizing and learning meaningful patterns. This is common in early stages when the model is not trained on a large, diverse dataset.

![GNN Image](/read_img/3.png)

*Explanation:*  
GNNs are used to model complex relationships and dependencies in the data. In this case, the fluctuating loss indicates the model is not yet able to make accurate predictions, primarily due to data limitations.

---

## GCN (Graph Convolutional Networks)

**Accuracy:** 96.15%  
- **Training and Validation Loss:** Both show steady decline, indicating that the model is learning effectively.
- **Performance:** The model is well-performing with minimal overfitting, showcasing good generalization.

![GCN Image](/read_img/4.png)

*Explanation:*  
GCNs perform exceptionally well, with high accuracy and stable loss curves. This means the model is effectively learning the underlying patterns and is capable of generalizing to unseen data, providing accurate predictions.

---

## RAG (Retrieval-Augmented Generation)

**Training Curve:**  
- Around epoch 150, the curve starts to flatten, indicating the model has likely converged. Further training would not significantly reduce the loss.

![RAG Image 1](/read_img/5.png)  

*Explanation:*  
RAG combines retrieval-based techniques with generative models, enabling the system to provide relevant information by dynamically pulling data during training. As the model reaches convergence, it becomes more capable of retrieving relevant knowledge for project management insights.

---

## Llama Model

**Accuracy and Performance:**  
- High, steadily increasing accuracy indicates excellent model performance.
- A high **ROUGE** score confirms that the model aligns well with expected outcomes.

![Llama Image 1](/read_img/6.png)  
![Llama Image 2](/read_img/7.png)

*Explanation:*  
The Llama model is designed to understand natural language effectively. With its increasing accuracy and high ROUGE score, it can generate precise answers based on project management data, enhancing decision-making and optimizing project processes.

---

## Llama Model Input Example

**Input:**  
_"Provide a detailed 7-day mobile app development plan. Outline each day’s tasks, key milestones, and expected deliverables."_

![Llama Input Example](/read_img/8.png)

*Explanation:*  
The Llama model generates a structured, detailed plan based on the input query, helping project managers automate planning and task scheduling.

---

## Chosen Approach

To enhance the results further, we send the **Llama model** through an additional layer of fine-tuning using a more capable version of the model. This process improves the response quality and allows for more accurate planning, risk assessment, and scheduling.
 
By fine-tuning the Llama model and enhancing its capabilities, we ensure that the system can provide highly accurate, context-aware recommendations and insights. This iterative refinement helps prepare for risks, plan tasks, and schedule activities with greater precision.

---

### Get in Touch
Have questions or want to collaborate? Feel free to reach out or open an issue in the respective repositories!
