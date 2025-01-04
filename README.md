## **Overview**  
This project demonstrates how to leverage **Salesforce Einstein AI** and **Prompt Builder** to automate personalized **welcome emails** for resort guests. By integrating **AI-generated content** with **CRM data**, the system dynamically generates emails with guest-specific details, saving time and enhancing user engagement.  

---

## **Key Features**  

- **Einstein AI Integration**: Utilizes **OpenAI GPT-4** for generating personalized email content.  
- **Prompt Builder Templates**: Reusable **Sales Email Prompt Templates** for consistent and scalable communication.  
- **Dynamic Merge Fields**: Pulls guest reservation data directly into emails, ensuring accurate and up-to-date information.  
- **Data Cloud Enrichment**: Combines CRM and external reservation data seamlessly for a unified workflow.  
- **Email Automation**: Streamlines email workflows, allowing for efficient sales communication.  
- **Flexible & Scalable**: Templates can be adapted for multiple scenarios, including promotional offers and check-out messages.  

---

## **Tech Stack**  

- **Salesforce CRM**  
- **Einstein GPT-4** for AI-generated content  
- **Prompt Builder** for reusable templates  
- **Flow Builder** for automation workflows  
- **Sales Cloud & Data Cloud** integration  

---

## **Project Workflow**  

1. **Setup Environment**:  
   - Enable **Einstein AI** and **Sales Cloud** in Salesforce.  
   - Create **lookup relationships** between guest events and external reservations.  

2. **Data Preparation**:  
   - Define **Guest Events** and **Reservations** to store guest data.  
   - Establish relationships to dynamically merge information into email templates.  

3. **Prompt Template Creation**:  
   - Build a **Sales Email Prompt Template** with placeholders for guest details.  
   - Configure **merge fields** for real-time data insertion.  

4. **Testing and Activation**:  
   - Preview template output for sample guests and reservations.  
   - Activate templates for live usage.  

5. **Email Automation**:  
   - Use Einstein's **Draft with AI** feature to generate emails based on the template.  
   - Send personalized emails to guests with accurate and engaging content.  

---

## **How It Works**  

1. Guest data is populated in **External Reservations**.  
2. A **Guest Event** links to the reservation via a **lookup relationship**.  
3. The **Prompt Template** dynamically pulls reservation details (check-in date, room type, etc.) and formats an email.  
4. Einstein AI generates the email body, title, and subject line, following predefined instructions.  
5. Users can review and refine content before sending, ensuring flexibility and quality.  

---

## **Use Cases**  

- **Hospitality Industry**: Automate guest welcome, check-out reminders, and promotional offers.  
- **Sales Teams**: Send pre-filled follow-ups or appointment reminders.  
- **Customer Support**: Deliver onboarding guides and FAQs based on customer needs.  

---

## **Getting Started**  

1. **Deploy Salesforce Components**: Import objects, relationships, and templates into your Salesforce instance.  
2. **Enable Einstein AI**: Activate AI and Sales Email features in your Salesforce org.  
3. **Test the Workflow**: Create sample guest reservations and preview the email output.  

---

