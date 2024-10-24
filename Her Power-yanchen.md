# Her Power: Door-to-Door Repair Service Platform for Single Women

### 1 Introduction
In recent years, as women's awareness has grown, higher education has expanded, and society has rapidly advanced, more women are choosing to delay or forgo marriage, prioritizing career development and personal growth. This trend has resulted in a significant rise in the number of women living alone. However, the safety of women living alone has been largely overlooked, particularly regarding male service providers such as repairmen, cleaners, and delivery personnel, who may pose security risks. Despite the growing concern, there are currently no products or services that specifically address this issue. With the increasing age of first marriages, rising divorce rates, and declining fertility, the number of women living alone is set to increase, making their safety concerns even more pressing.

This project aims to address this gap in the market by providing female home-service providers, such as female repair technicians and cleaners, specifically for women living alone. The goal is to offer a safer alternative for in-home services, reducing the security risks that come with traditional door-to-door services.

![](https://github.com/KaltsitsPie/picx-images-hosting/raw/master/1.6pnibbs2un.webp)


### 2 Innovation Points and Project Features
#### 2.1 Practical Problems Solved

1. So that women living alone can avoid male repairmen home service security risks, timely solution to the problem;

2. It is different from the traditional housekeeping service model, which makes the service of female repairwoman more efficient, and avoids the safety risk of providing men with home service;

3.  User complaints to facilitate the development team timely improve the small program design, service processes and other issues to further improve the security of services.

#### 2.2 About Her Power
1. Identify gaps in the market and target customer pain points

The product is based on the long-neglected group of women living alone to the security of home-based services, clear target customers, a large number of strong targeted and practical value. At present, there is no special platform for women living alone to provide home services, and the demand of women living alone in this area is inevitable, so this product has a strong pioneering and irreplaceable.

2. Break through the traditional product model to meet the two-way demand

Female service providers, especially workers, have been discriminated against in the job market for a long time, and female employment is often more difficult than male employment. Based on this phenomenon, the product innovatively breaks the traditional“With a service to solve a problem” model, focusing on current social problems, with a product to solve the single female home service safety, female repairman employment two-way demand.

3. Improve the security mechanism to ensure the safety of users

To ensure the personal safety of repairmen and customers, the product uses measures such as facial recognition to ensure that both sides of the service are female. Face recognition is required to verify gender when a customer places an order or when a repairman takes an order; both parties can lodge a complaint and immediately terminate the service if any problems arise during the service, human Services will be the first to step in. Manual customer service will be based on the use of blackout, deduct margin and a series of methods for offenders to be punished.

4. Remove sensitive data in time to protect users' privacy

The product always puts the protection of user privacy first. The product only saves the user's personal information for the time necessary to achieve the goal. When the order is completed, the system will delete the contact phone number and address information of the customer. At the same time, the system undertakes not to share users' personal information with third parties without their permission (except under special circumstances as required by law) , as detailed in Appendix 1, Privacy Guidelines.

### 3 Product Design
#### 3.1 Design Principle
Following the principles of simplicity, user-friendliness and focus on serving female users, we have designed the UI with cartoon yellow chicken as the main element and bright and lively yellow as the theme color, the little yellow chicken in repairman's clothes fits the position of this project's door-to-door maintenance service. The following is part of the design drawing.

![](https://github.com/KaltsitsPie/picx-images-hosting/raw/master/2.8ojp1yk4r6.webp)

#### 3.2 Page Redirection Logic
##### 3.2.1 Customers

![](https://github.com/KaltsitsPie/picx-images-hosting/raw/master/3.2rv4uy6w73.webp)

##### 3.2.2 Repairman

![](https://github.com/KaltsitsPie/picx-images-hosting/raw/master/4.99tco9iymw.webp)

##### 3.2.3 Admin

![](https://github.com/KaltsitsPie/picx-images-hosting/raw/master/5.2obix8fzin.webp)

#### 3.3 Interaction Principles
##### 3.3.1 Intuitive Category layout on the Homepage

Her Power applet provides a variety of home maintenance services, applet home using modular layout, will be divided into categories of all services displayed, with the icon tone consistent border so that classification more at a glance.

![](https://github.com/KaltsitsPie/picx-images-hosting/raw/master/6.lvq96o8vg.webp)

##### 3.3.2 User Error Tolerance

When a user places an order, if the time or invalid address is entered beyond the allowed range, the order will be rejected and the user will be prompted to check the input and try again, increasing fault tolerance.

##### 3.3.3 Security Alerts

Users will receive the security tips as shown in the picture when they confirm placing an order or accepting an order, reminding users of their personal safety and initiating complaints in a timely manner.

![](https://github.com/KaltsitsPie/picx-images-hosting/raw/master/7.2yycqe2t14.webp)

##### 3.3.4 Orders Efficiently by Distance

Repairmen's order lists are ordered from near to far. Repairmen can quickly select orders with the right distance and service time to take orders, which is very efficient.

![](https://github.com/KaltsitsPie/picx-images-hosting/raw/master/10.39l6jjz3ml.webp)

##### 3.3.5 Lovely Chicken in Blank Page

When the user's order list, available order list, evaluation list, etc. when the list is empty, applet will show a lovely chicken, so that the page is no longer monotonous.

![](https://github.com/KaltsitsPie/picx-images-hosting/raw/master/9.5fkl5bcj8g.webp)

##### 3.3.6 Complaint

To access the appeal interface, the user can choose the type of appeal 1.5. Non-female 2. Otherwise, type in the complaint's problem description, and the end user must provide a contact number. After successful complaint, it will be returned to the order list.

![](https://github.com/KaltsitsPie/picx-images-hosting/raw/master/11.b8wg1tk6g.webp)



##### 3.3.6 Feedback 

Both users can evaluate each other after the order is completed. There are two parts to the evaluation, one part is the rating, the other part is the details of the evaluation. Reviews are returned to the order list after they have been submitted.

![](https://github.com/KaltsitsPie/picx-images-hosting/raw/master/12.99tcoadm5b.webp)


##### 3.3.7 Safe and Reliable User Experience

The applet will not collect personal information of the user without the user's authorization. It will not collect sensitive information of the user in any form. Details are as shown in the figure below. A pop-up window will be displayed to seek the user's consent when requesting authorization.

### 4 Technology Used
#### 4.1 development environment

1. WXSS, WXML;

2. Wechat applet base version 2.14.1 and above;

3. The database uses the wechat small program cloud database;

4. Wechat client version 7.0.19 and above.

#### 4.2 third party resources

1. Alibaba vector icon library

2. Ink Knife built-in construction library;

3. Tencent technology (Beijing) Co. , ltd.-address resolution API;

4. Face detection and analysis API, shenzhen-based Tencent Computer Systems Co. , Ltd. .

#### 4.3 backend technology

Small program using wechat small program cloud development model, no need to build a server can be rapid small program back-end development. The cloud development capabilities used by the applet are cloud functions, cloud storage, cloud database, and cloud calls, the cloud database is used to store the information necessary for small programs to provide services, such as login user information, token, order information, Evaluation and appeal information, etc. , that is, repair certificates and photos describing what needs to be repaired; cloud functions are used to check the validity of information and operate cloud databases for use by the front end of the applet.

#### 4.4 Test Environment

|  Test 1 |   |
|:----------|:----------|
| Operating System    | Android 10.0    |
| RAM    | 8.00GB    |
| Processor or CPU    | Qualcomm Snapdragon 765    |

|  Test 2 |   |
|:----------|:----------|
| Operating System    | iOS 13.3.1    |
| RAM    | 3GB   |
| Processor or CPU    | A12    |

![](https://github.com/KaltsitsPie/picx-images-hosting/raw/master/13.6ikag7sdrx.webp)

