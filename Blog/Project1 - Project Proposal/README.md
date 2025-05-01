## PROJECT 1 - PROJECT PROPOSAL

## 1) Problem 🤔
## 1.1 Description of Problem Space
Access to legal aid is crucial for ensuring justice and protecting rights, but many young people, immigrants, and marginalized communities face significant barriers when seeking legal help. Three main problems that can be seen as barriers are: complexity and legal jargon, outdated, non-mobile-friendly interfaces, and fear of formal institutions along with a lack of anonymity.
These issues hinder equal access to justice, which is a key focus of UNESCO’s Sustainable Development Goal 16: Peace, Justice and Strong Institutions. Addressing these barriers is essential to build inclusive and accessible legal systems for all.

## 1.3 Problem 2: Non-Mobile-Friendly, Outdated Interfaces
In the digital age, mobile accessibility is essential—especially for young users, marginalized communities, and immigrants who often rely on smartphones as their primary or only means of accessing the internet. However, many official legal aid or reporting websites in Malaysia remain outdated, difficult to navigate on mobile devices, and not optimized for intuitive use. This creates significant barriers for individuals who may already struggle with language challenges, limited digital literacy, or unstable internet access. For these users, particularly during urgent or distressing situations, the inability to quickly and easily access legal help via mobile can result in delays in justice, increased vulnerability, and a sense of helplessness. A lack of responsive, mobile-friendly design effectively excludes the very communities that most need accessible legal support.

### Desktop vs Mobile View – Jabatan Bantuan Guaman (JBG) Website

<img align="center" width="30%" src = "1.3.0.png" ><br>
Full screen PC view of JBG website

**Figure 1.3.0. Full screen PC view of JBG website**

![Mini-window view of JBG website](Blog/Figures/1.3.1.png)  
**Figure 1.3.1. Mini-window view of JBG website**

![Mobile view of JBG website](Blog/Figures/1.3.2.png)  
**Figure 1.3.2. Mobile view of JBG website**

The Jabatan Bantuan Guaman Malaysia (JBG) website is clearly optimized for full-screen desktop viewing. However, when accessed in a resized browser window or on a mobile device, the site exhibits significant usability issues. In the mini-window view, images do not resize appropriately, and in mobile view, overlapping icons obstruct the text while the layout becomes inconsistent and disorganized.

These problems violate the usability goals of **Accessibility** and **Effectiveness**, which stress that information should be easily viewable on smartphones, with large touch targets and clear navigation. The site also fails to meet UX goals of being **Accessible** and **Satisfying**, as it does not deliver a smooth, pleasant experience across devices.

### MyJanjiTemu Interface Issues

![Interface of MyJanjiTemu](Blog/Figures/1.3.3.png)  
**Figure 1.3.3. Interface of MyJanjiTemu**  
*Source: [MyJanjiTemu](https://aplikasi.jbg.gov.my/myjanjitemu/index.php#features)*

Within the JBG website, the **MyJanjiTemu** feature is designed to allow users to make legal advising appointments. However, the top-right directory button is non-functional, suggesting that the feature is either incomplete or poorly maintained. As a result, users cannot access essential services like checking available services, branch locations, office hours, or an FAQ section.

### Malaysian Bar Council Website

![Interfaces of Malaysian Bar Council](Blog/Figures/1.3.4.png)  
**Figure 1.3.4. Interfaces of Malaysian Bar Council (Badan Peguam Malaysia)**  
*Source: [Malaysian Bar](https://www.malaysianbar.org.my/)*

The Malaysian Bar Council website relies heavily on dense text, minimal visuals, and a limited color palette. This contributes to a dry, cognitively demanding user interface that is not engaging for young or less literate users. This contradicts key UX goals such as being **Enjoyable**, **Cognitively Stimulating**, **Emotionally Fulfilling**, and **Motivating**.

---

## 1.4 Problem 3: Fear of Formal Institutions and Lack of Anonymity

Recently, an AI deepfake scandal at Foon Yew High School raised serious concerns about digital safety and trust in institutions. A female student revealed that her photo was used to generate explicit AI-generated images, which were sold and distributed online. Despite the severity of the case, her request to report the incident to police was rejected by a school authority—allegedly to protect the school's reputation. The perpetrator received only minor disciplinary action.

![Screenshot of victim’s statement](Blog/Figures/1.0.png)  
**Figure 1.4.0 A screenshot of a victim’s statement posted on Instagram**

This case highlights the fear and mistrust many victims feel when seeking help from formal institutions. The school’s passive response and lack of confidentiality discouraged others from coming forward. Only after the incident went viral on social media did more victims—some as young as 14—share their experiences.

From a **Usability and UX** perspective, this reveals major flaws in current reporting systems. The absence of an **anonymous**, **intuitive**, and **emotionally supportive** reporting tool created a barrier for victims who feared stigma or retaliation. UX design in this context should focus on **safety**, **emotional reassurance**, and **ease of use**, particularly for young or vulnerable users.

To encourage reporting and protect users, legal aid systems must align with usability goals such as **Learnability**, **Accessibility**, and **User Confidence**, and UX goals like **Emotional Satisfaction** and **Trust**. These principles are essential to build tools that empower users to seek help without fear.

## 2) Proposed Solution 💡

### 🦸🏻JustiLink 

A human-centered legal aid platform specifically designed for disadvantaged groups such as young people, migrants, and marginalized populations.Unlike traditional legal aid methods, JustiLink focuses on:

- A mobile-first design approach
- Integration of visual and multilingual assistance
- User privacy through anonymous help interface

### 🧩 Key Features of JustiLink

#### 1.  Simplified Legal Content 📋

One of the primary issues users face with current systems is overly complex of legal language. JustiLink solve this problem through several solutions:

#### - Plain Language Rewriting
- All legal content is rewritten in plain, conversational language.
- Complex legal terms are translated into simpler equivalents.

#### - Visual Step-by-Step Guides
- Legal issue comes with the flowcharts, diagrams, or illustrations.
- Based on dual coding theory,which combining text with images signifantly enhances understanding and memory.

#### - Educational Videos
- Short multilingual videos (1–3 minutes) on explaining processes and users' rights through real-life scenarios
- Delivered in local accents with subtitles and are highly relatable and comprehensible.

#### - Multilingual Support and Accessibility
- Offers translation in Malay, English, Tamil, Mandarin, and Bahasa Indonesia.
- Accessibility features include:
  - Text-to-speech
  - Change in font size
  - High-contrast mode are built into the interface to support users with visual impairments or reading difficulties.

#### - HCI Principles Applied
- Cognitive load reduction through simplified content and visuals
- Recognition over recall using icon-based categories
- Inclusive design ensures access across diverse users


#### 2. Mobile-First, User-Centered Interface 📱
JustiLink is developed using a mobile-first strategy, recognizing that mobile is the primary access point for many users.

#### - Responsive and Simplified UI
- Optimized for small screens with:
  - Minimal text
  - Large icons
  - Easy-to-use navigation paths
- Icons represent legal topics visually(🏠 = landlord issues, ⚖️ = justice)

#### - Guided Navigation and Progressive Disclosure
- Users go through a step-by-step flow with only essential information shown at each stage.

#### - Smart Search and Categorization
- Keyword suggestions based on user input
- Legal issues are categorized by themes like:
  - “Workplace Issues”
  - “Family Law”
  - “Student Rights”

#### - Feedback and Affordance
- Real-time feedback(animations, confirmations, haptics)
- Interface design based on user expectations

#### - HCI Principles Applied
- Mobile usability which tailored for handheld devices with minimal scrolling and fast load times
- Progressive disclosure which reduces information overload and improved focus
- Visibility of system status which ensures users are always aware of system status


#### 3. Anonymous First Chat Feature 🤫
To eliminate the fear of judgment, exposure or retribution, JustiLink offers an "Anonymous First Chat" to build trust and reduce user hesitation.
#### - Zero-Barrier Entry
- Users can initiate the conversation without registration or sharing personal information.

#### - Chatbot and Human Hybrid Model
- NLP chatbot addresses general legal queries from a trained knowledge base.
- Escalate to human legal consultants without restarting the conversation.

#### - Gradual Disclosure for Sensitive Users
- Users are encouraged to register an account for additional services such as scheduling appointments or file uploading. 

#### - Secure, Encrypted Conversations
- Conversations are end-to-end encrypted.
- No data is retained without their permission.

#### - Empathetic Interaction Design
- Chat interface is designed with a calming color palette and friendly microcopy like “You're not alone".

#### - HCI Principles Applied
- Trust-centered design which builds confidence through anonymity and security.
- Affective computing which interface elements are emotionally intelligent and empathetic.
- Low-commitment interaction which reduces entry friction and encourages trial use.

## 3) Target Users 🎯
### 👥 Making Legal Help Accessible for All

JustiLink is designed to solve and address legal problems for people from different social backgrounds. The key target user groups are:

- **Youths**
- **Immigrants**
- **Low income families**

These groups often face legal issues but lack of suitable platform that provides useful solutions. Here's how JustiLink supports each of them:



### 👩‍🎓 Youths  

**Why they need JustiLink:**

- Frequently experience legal problems whenever in daily life or online.
- Lack of awareness of how to protect themselves legally.
- Might have faced bullying or digital harassment.
- Unable to find a trustworthy legal institution and fear seeking help.

**How JustiLink helps:**

- Offers an “anonymous first chat” feature to reduce the fear of judgment.
- User friendly with providing simplified language to access legal information and take appropriate action.


### 🌍 Immigrants  

**Why they need JustiLink:**

- Lack of proficiency in the local language.
- Difficult to seek advice and understand legal documents.
- Risk of exposure when dealing with sensitive concerns like immigration status.

**How JustiLink helps:**

- Provides multilingual support by making legal information accessible to non-native speakers.
- Legal services are categorized by issues such as labor disputes and housing issues, making it easier to find and access the relevant support.
- Includes an anonymous feature allows users to seek advice discreetly.


### 💸 Low-Income Families  

**Why they need JustiLink:**

- Often unable to afford legal service.
- Face important legal matters such as housing disputes or family matters.
- Fear or concern about being judged due to their family and social background.

**How JustiLink helps:**

- Provides easy access to free or low-cost legal resources to ensure financial barriers are able to solve important legal matters.
- Provides emotional safety through anonymous features.
- Encourages users to seek help without fear of discrimination.

