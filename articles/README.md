[Understanding adversarial examples requires a theory of artefacts for deep learning](https://www.nature.com/articles/s42256-020-00266-y.epdf?sharing_token=AXS_MsZfvS8gFZtAJlIOq9RgN0jAjWel9jnR3ZoTv0PIZwnfXXIXpRQcD8xNIztDgZC5kD2o055PXQPDNV8KY1LuP1rScFebb1ZGCMg0qXYLzlK3fcTeCCGN-fHk0QiLTzxj_VmBnCpW77ZZ_BFvGrZd09ducRIIkPNN0-HeD1c%3D)
>Deep neural networks are currently the most widespread and successful technology in artificial intelligence. However, these systems exhibit bewildering new vulnerabilities: most notably a susceptibility to adversarial examples. Here, I review recent empirical research on adversarial examples that suggests that deep neural networks may be detecting in them features that are predictively useful, though inscrutable to humans. To understand the implications of this research, we should contend with some older philosophical puzzles about scientific reasoning, helping us to determine whether these features are reliable targets of scientific investigation or just the distinctive processing artefacts of deep neural networks.



[Repp Health Uses AWS to Track Medical Assets to Within 10 Centimeters](https://aws.amazon.com/pt/solutions/case-studies/repp-health-case-study/)
> sing number of devices used in medical procedures, patients must often wait while hospital employees search for equipment, open beds, and key personnel. The patient frustration and harm that can result would be reason enough for hospitals to seek intelligent monitoring of the movements and locations of people and equipment.
>
>There are additional reasons for intelligent monitoring in healthcare. The more hospitals know about staff movement patterns, the better they can advance workplace health and safety while managing personnel efficiently. Also, hospital administrators need an accurate picture of what equipment they already own and how it is being used in order to develop organization-wide purchasing strategies.
>
>Repp Health was founded in 2018 to serve those needs. The startup offers Repp Locate, a cloud-based tracking solution that uses Internet of Things (IoT) sensors to locate medical assets, staff, and patients in real time with 10-centimeter accuracy using ultra-wideband technology. Another solution, Repp Vision, uses radar sensors placed in rooms to monitor and update electronic health records with patient movement, such as falls, and the presence of staff and other visitors without the use of body-worn sensors. Both solutions run on a serverless Amazon Web Services (AWS) IoT architecture.
>
>"Our solutions were born on AWS because we were a startup with limited resources," says David Sachs, Repp Health CEO and a cofounder. "We estimate that running on AWS enabled us to get to market with a solution that can scale to serve the needs of the largest healthcare providers in the nation at one-third the cost of alternate approaches. This is not only because we avoid the cost of physical infrastructure, but also because we can take advantage of off-the-shelf IoT services that help us move quickly.”

***Next-Generation Real-Time Location Services (RTLS) in the Cloud***

>Although the idea of tracking assets and people on medical campuses is not new, traditional solutions have limitations. "Legacy tracking services rely on sensors that provide binary, yes/no information, such as whether one sensor is close to another one," says Dan Fox, the chief technology officer for Repp Health. "Those solutions have heavy infrastructure requirements and can deliver ambiguous or inaccurate information. Our solution provides precise x, y, and z coordinates with up to 10 times more accuracy than traditional RTLS and a lightweight on-site footprint. We see an opportunity to bring tracking to the next level, with much more accurate location intelligence and valuable new categories of information."
>
>Sachs says that this opportunity was created in large part by cloud computing. "Without the flexibility and scale available in the cloud, our offering would have been a non-starter. After comparing cloud vendors, we picked AWS based on the breadth and maturity of its services and the viability of a serverless, HIPAA-compliant architecture."
>
>Repp Health's location intelligence solutions use AWS IoT Core to connect tracking tags or in-room radar sensors to the cloud. The solutions use Amazon Kinesis Data Streams, Amazon Kinesis Data Analytics, and Amazon Kinesis Data Firehose to handle the ingestion, monitoring, and analysis of data stored in an Amazon Simple Storage Service (Amazon S3) data lake.
>
>One of Repp Health's main differentiators is its Amazon CloudFront–hosted web interface, which uses real-time location information stored in Amazon DynamoDB to provide hospital staff with a live, blue-dot experience similar to that of popular mobile navigation apps.
>
>The key to this user experience is the subscriptions feature of AWS AppSync, a managed service that uses GraphQL to enable highly scalable applications to securely access, manipulate, and combine data from multiple sources. "The AppSync subscriptions feature enables us to provide situational awareness to healthcare providers in real time and at limitless scale,” says Fox.

***Simple HIPAA Compliance and a Light Footprint on AWS***

>By building its solutions on AWS, Repp Health was able to release its products to market quickly with a lean team. "On AWS, we built a sophisticated production app from scratch in just seven months with a very small team," says Fox. "Even three years ago, this kind of development process would have taken twice as many people and significantly more time to complete."
>
>Using AWS tools, it was much simpler to achieve the compliance without which the company's products would have been useless to the healthcare field. "HIPAA compliance and other privacy protections are something we and our customers take very seriously," says Sachs. "With the large number of serverless HIPAA-eligible AWS services, we didn't need a large team or lots of time to tick all the boxes for HIPAA compliance."
>
>Regarding data security more generally, Repp Health is finding that the strong reputation AWS has in this area is reassuring to customers. "One thing that keeps hospital CIOs up at night is overall security," says Fox. "At the hospitals we're talking to, we find that once we explain that our products run on AWS, security conversations get a lot simpler."
>
>CIOs also appreciate the light footprint of Repp Health solutions. "By running on AWS, we're able to offer very sophisticated technologies on a software-as-a-service model," says Fox. "The fact that we can take hospitals' location intelligence to the next level without having to install yet more equipment on their already-crowded premises is a strong selling point."
>
>Because the solutions are serverless, it's easy for Repp Health to onboard new customers and scale up existing ones. "With a serverless AWS architecture, we don't have to plan ahead for servers," says Danny Lovelace, software engineer for Repp Health. "As we add new hospitals, floors, and buildings—or even new data sources—we just manage and configure our services while the solution scales as needed."
>
>The serverless architecture also lays a foundation for future integrations and growth. “Improving outcomes and lowering costs are critical today for both healthcare providers and patients, but it’s hard to improve what you can’t see,” says Sachs. “With the situational intelligence we can obtain through IoT, it’s possible to observe the whole care process. AWS enables us to have the flexibility to integrate, measure, and take action on a suite of new data sources.”

***To learn more, visit [aws.amazon.com/health](aws.amazon.com/health)***.
