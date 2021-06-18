# Appendix 1 Dmartech Glossary

### Contacts

All personnel data in the platform are contacts data.

### Followers

Contacts who are following WeChat official account.

### Primary Key

Contact attributes that can be used as the unique identity of a contact, such as mobile phone number, email address.

### Real Name Contacts

Any value with a primary key attribute is a real name contact. That is, the identity of the contact is clear.

### Anonymous Contacts

An anonymous contacts is someone with no primary key attribute value, such as anonymous visitors to the website.

### Contacts Attribute

Contact attributes and behavior events \(that is, events generated by contacts\) are the most basic data of Dmartech. These data can be used to help Dmartech improve the user portrait and analyze the data effectively. The contact attribute mainly uses some fields to improve the contacts information, such as name, mobile phone number, email, age, company, etc. This information can come from contact data upload or creation, or can be submitted by the customer, the system automatically grabs contact information.

### Behavioral Events, Event Attributes

Some behaviors of contacts will be automatically recorded by the system in the form of behavioral events. For example, mail events include open mail and click mail. Dmartech will automatically record when the contact has the above behaviors, then event attributes are the name of the opened mail, the time when the behavior occurred, etc. which can be used to describe and filter events.

### WeChat Management

Accounts which have already bound to WeChat official accounts can use WeChat modules in Dmartech. All functions of the WeChat module rely on the functions of the WeChat public background. The main functions are follower management, Content management, send WeChat message, customized menu of WeChat official account and automatic reply setting, which can be synchronized with the corresponding content of the WeChat background in real time.

### QR code

The QR code created and managed in Dmartech is a QR code with parameters. In order to meet the needs of user channel promotion analysis and other scenarios, QR codes with different scene values can be created. After the user scans, the official account can receive event pushes.

### Label, Follower Label, Contact Label

**Label** is used to mark the characteristics of a contact. It is also used to portray contact portraits, as well as classify and identify contacts. 

**Follower Label** is the label added to WeChat followers. It is used to classify and mark WeChat followers. Its addition and management are on the page of **WeChat &gt; Follower**, and are synchronized with the WeChat public background. 

**Contact Label** is a label on the page of **Data Center &gt; Tag mgt**, it can be used to mark and classify all contacts.

### Mass Message, Customer service message, Template message

**Mass Message** is a general message sent to followers in bulk, such as graphic push. Followers can receive up to 4 mass messages per month. 

Only followers who interacted with the official account within 48 hours can receive **customer service messages.** 

**Template message** is used to send important service notifications to followers.

### Contacts Management

All contacts list is shown on the page of **Contacts &gt; Contacts**. It is classified by real name contacts, anonymous contacts, and WeChat fans contacts. You can search, query and edit contacts data as need.

### **Contacts Segment**

Segments are groups of contacts generated based on filter criteria and contact lists. Segments can filter contacts based on criteria like contacts attributes or behavioral events. Segments are used as audience in a journey.

### **Content**

You can see there are two types of content in Dmartech. 

Content in WeChat &gt; Content indicate WeChat images, videos, audio, graphics, etc. 

Content in Marketing &gt; Contents indicate email, SMS and MMS which can be used in marketing journeys.

### **Marketing Journey**

Marketing is to let customers buy our services or products by means. 

The marketing journey is to gradually implement the marketing plan to form a path, and the user completes our marketing plan after entering the journey and completing the path. For example, placing an elephant in a refrigerator requires three steps: opening the refrigerator, placing the elephant, and closing the door. In the same way, the marketing journey is not complicated, just build and set up the marketing plan step by step, and form a reasonable process. For example, select a group of contacts, determine whether they are interested in sports shoes, and send them product introductions related to sports shoes.

### **Event**

The behavior of contacts is recorded by events. For example, a contact logged into the company's official website and submitted a trial form. Then here involves "login event" and "form event". For more details, please see Metadata.

### Channel, Task

Channels indicate the media methods that can reach users, such as email channels, SMS channels, and WeChat channels.

 One delivery from any channel is a task.

### Milestone

Set milestones in the journey to view the number of contacts who have reached a certain step and use it to analyze marketing effect. 

Form, Gold Data Form, Dmartech Form 

**Form**: The form is used to collect contact information. The form created in Dmartech can be sent by QR code or template message. After the contact fills in and submits the form, the data will be automatically synchronized to Dmartech in real time. 

**Gold Data Form**: Dmartech is connected to the gold data form. Users can create a form on the gold data platform, associate and synchronize on the Dmrtech platform, and then directly use the gold data form. 

**Dmartech Form**: Forms created and managed on the Dmartech platform.

### Data Center

The basis of marketing is contact data. Data center provides multiple data access methods to manage and record data import records and detailed logs.

### **Meta Data**

Dmatech data is divided into two categories: contact attribute data and contact behavior event data. Metadata is the definition of these two types of data, including specific property name, filed meaning, field type and other information.

### Online marketing activities

Online marketing activities refer to journey reports, you can view journey reports, mission sending reports, and export report data.

### Total of emails sent, Total of emails accepted, Unique emails opened, Unique emails click-throughs

**Total emails sent**: The total of emails which have been sent. 

**Total emails accepted**: The total of emails which have successful sent to recipients. Accepted = Sent – Hard/Soft bounced 

**Unique emails opened**: The unique number of contacts that an email is displayed. When a Contact clicks on at least one link or accepts viewing the images, one unique email open is registered, even when the Contact opens the email more than one time subsequently.

**Unique emails click-throughs**: Number of clicks by unique contacts on one or more links in the email. It doesn’t matter if the contact clicks on three different links or three times on one link. In both these cases they count as one unique click.

### **Event Analysis**

Any event-related analysis can be performed by setting event conditions to form an analysis chart.

### **Contact Analysis**

Any attribute analysis can be performed by setting attribute conditions to form an analysis chart.

### Segmentation

Set conditions based on contacts attributes and what the contact has done, and combine logical operators such as "and", "or" to classify contacts.
