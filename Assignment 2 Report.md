# The Rise of Deepfake Technology: Implications for Cybersecurity in Malaysia

## INTRODUCTION

### Overview of Deepfake Technology

As technology continues to grow, especially Artificial Intelligence (AI), we are starting to see a greater spread of AI usage in the 
workplace in our everyday lives, particularly in industries such as healthcare, education, and finance. One such use case of AI is deepfake 
technology, which threatens the cybersecurity of online users. Deepfake is a combination of the terms "deep learning" and "fake", 
signifying its use of deep learning algorithms in creating fakes, which include swapping faces in videos or entirely faking audio 
recordings or images of people who don't exist (Proofpoint, Inc., n.d.).

Deepfake technology continues to pose a considerable and evolving threat to cybersecurity. Deepfake technology is increasingly used to 
create a variety of malicious activities that exploit human trust and vulnerability to various digital attacks. Some vulnerabilities 
created by deepfake technology include impersonating another person, fraud, spreading disinformation and misinformation, potential invasion 
of privacy, identity theft, reputational damage, and sometimes they are used by countries employing such technology and utilising it as a 
tool in cyber warfare.

### Purpose of the Report

The purpose of this report is to analyse the definitions, potential uses and abuses of deepfake technology. The report will analyse the
state of cybersecurity in the context of deepfake technology in Malaysia, and analyse the opportunities for societal, legal and ethical 
issues associated with deepfake technology. The report will investigate what the cybersecurity space in Malaysia looks like, highlighting 
vulnerabilities where deepfakes could be a concern.

Additionally, this report will examine the social implications and concerns of deepfake technology in presenting misinformation, infringing
on the privacy of individuals, and causing harm to individuals and their communities. This report will analyse to relevant regulations in 
Malaysia, such as the Malaysian Communications and Multimedia Commission (MCMC) guidelines, regulations in the Penal Code regarding fraud,
and the Malaysian Personal Data Protection Act (PDPA) regarding data misuse.

Furthermore, this report will highlight key protective measures that organisations can implement to protect vital digital assets and 
resources from deepfake threats. Finally, this report will provide recommendations for enhancing cybersecurity practices associated with 
deepfake threats. 

## DEEPFAKE TECHNOLOGY

### Deepfake Technology and Its Mechanics

Deepfakes are AI-manipulated media, either video, photos, or audio recordings that seem very credible. Deepfakes can replace, manipulate, 
and synthesise speech and faces. Deepfakes can make an individual appear to say or do something that they never did (Howard et al., 2020). 
The use of deepfake technology relies on complex AI algorithms, primarily autoencoders and Generative Adversarial Networks (GANs). An 
autoencoder is an artificial neural network that learns to recognise patterns, such as a person's face in a dataset, and reconstructs that
face. A GAN has two competing neural networks the generator that generates the deepfakes, and the discriminator, which attempts to 
recognise the deepfakes. These neural networks compete against and learn from each other, which means the generator will create better 
fakes based on the feedback it receives from the discriminator (Howard et al., 2020).

The basic mechanics of deepfake technology can be broken down into a few key steps. It all starts with data collection. A large dataset, 
which includes hundreds or even thousands of images, videos, or audio of the target person, is collected. When gathering the data, a 
recommended best practice is to gather data from different angles, with different lighting, and with different expressions, to diversify 
the dataset. The more diverse the dataset, the more realistic the final deepfake will be. The next step is training the dataset on a deep 
learning algorithm, such as an autoencoder or GAN. It is trained using the dataset to identify the unique facial features, expressions, and 
motions of the target, so it can learn about the visual and behavioural characteristics of the target. After the model is trained, it can
create new content, such as swapping one person's face with that of another, or synthesising a new voice that is similar to the target 
person's voice. Training the GAN is an iterative process in which the output is constantly refined until the model replicates the maximum 
amount of realism (Proofpoint, Inc., n.d.).

### Beneficial and Harmful Applications

Deepfake technology can be used in many positive and beneficial ways in multiple fields, including entertainment. The film industry, for 
example, is being revolutionised by deepfake technology, which allows filmmakers to have more realistic visual effects, digitally replicate
dead actors, and make actors look younger (Glick, 2023). Disney has already utilised deepfake technology to de-age an actor in The 
Mandalorian. Deepfake technology can also enhance the learning experience and engagement with students through interactive experiences. 
Students may be able to interact with virtual figures that are responsive and able to react in real time. For example, deepfake technology
could create simulated patients with realistic clinical conditions that allow students to practice diagnosis and communication without any
consequences (Agarwal et al., 2024).

Although deepfake technology does have some beneficial applications, it is important to acknowledge that there are harmful uses for it, 
too. One harmful use is for disinformation or misinformation through fake news. For example, deepfakes can be used to spread disinformation 
and misinformation about things like conspiracy theories or false ideas (Fortinet, Inc., n.d.). This can fool people into thinking that 
trusted individuals have said or done things that they have not. This can erode trust in media and journalism, creating a barrier to seeing
the truth. Another dangerous use of deepfake technology is fraud and scams. Deepfakes can also create identities or steal identities from 
real people. Scammers can use this for identity impersonation in voice or video contexts to pry someone into transferring funds.

### Ethical Concerns Associated with Deepfakes

The capability of deepfake technology to create hyper-realistic media through video, audio, and images hinders the public's ability to 
authenticate the media they see on the Internet. This poses some ethical concerns associated with deepfakes among the public. One of these 
concerns includes the erosion of trust in the media. As deepfake technology becomes more accessible with technological progress, it will be
much easier and cheaper to create fake news that looks legitimate. Deepfake technology can be used to create false narratives to 
intentionally mislead the public, making it difficult for individuals to trust what they see or hear (Vaccari & Chadwick, 2020). When 
everything on the Internet can become untrustworthy and unreliable, it can really damage trust in the public, cause chaos in a community, 
and lead to mistrust among the public. In particular, someone could use deepfake technology to maliciously damage or slander another 
person's reputation.

A different possible concern that might arise involves its ability to manipulate politics, especially during elections. It is feasible that
politicians could harm their opponents' reputations in order to persuade voters to support them. They could easily accomplish this by 
generating deepfakes of their opponents to spread inaccurate information or to provoke conflicts. It is quite possible that voters may not 
be educated enough to differentiate between real and fake information, making them more gullible to believing in deepfake content. After 
all, it has already happened publicly on social media, where deepfake content of the US candidates making controversial comments, intended 
to manipulate public opinion, was spread around. This action of misleading the public and creating confusion during an election 
demonstrates how deepfake technology can be weaponised for one's political gain (Proofpoint, Inc., n.d.). 

## CYBERSECURITY LANDSCAPE IN MALAYSIA

### Malaysia’s Current Cybersecurity Infrastructure

Malaysia's current cybersecurity infrastructure can be evaluated based on two categories, namely the laws and regulations, and the 
dedicated government agencies that oversee the cybersecurity sector of Malaysia. Two notable laws concerning cybersecurity include the 
Cyber Security Act 2024 (CSA) and Communications and Multimedia Act 1998 (CMA). CSA is an act that strengthens national cybersecurity by
regulating the National Critical Information Infrastructure (NCII), handling cyber threats, and licensing cybersecurity service providers
(Chan, 2024). CMA, on the other hand, focus on combating content that is inappropriate and inaccurate, with the intent to annoy, threaten
or harass any person online by way of fines or imprisonment (Ahmad et al., 2018). One section that has frequently been referred to when 
discussing cyber harassment issues is Section 211 under CMA.

Malaysia also has key government agencies that help maintain Malaysia's cybersecurity infrastructure. Prominent agencies include the 
National Cyber Security Agency (NACSA) and Malaysian Communications and Multimedia Commission (MCMC). NACSA was established in 2017 to 
implement national cybersecurity policy in an integrated and coordinated approach. They aim to establish a stable, safe and resilient cyber
environment that meets the economic and social needs of Malaysia. Moreover, MCMC, a regulatory body based on the Malaysian Communications 
and Multimedia Commission Act 1998, actively works to combat the spread of fake news, misinformation, and scams online (BERNAMA, 2025). 
They are collaborating with social media platforms and law enforcement agencies to take down malicious content and accounts, protecting
citizens from online fraud and manipulation.

### Vulnerabilities Specific to Deepfake Exploitation

Despite Malaysia's current cyberspace infrastructure, there are still many vulnerabilities that deepfake technology may exploit. One of the
top issues is that the public has poor digital literacy and digital awareness levels. In 2019, SJK(C) was prohibited from including the ICT
subject in the school curriculum due to its tuition fee. This controversy has sparked a big debate as it has decreased the digital literacy
among the students. Moreover, older generations living in rural areas where technology is less advanced may not be aware of deepfake 
technology. These have caused more people to fall victim to deepfake scams as they are not able to identify these scams and misinformation
(Vaccari & Chadwick, 2020).

Furthermore, deepfake technology appears to be threatening most biometric security controls. Nearly all companies and organisations have
adopted biometric authentication such as fingerprints, voice and facial patterns as a replacement for passwords. The challenge here is that
these biometric authentication systems are not being updated regularly to keep up with the evolving deepfake technology. Back in the day, 
these biometrics were difficult to replicate, but as deepfake technology has improved over time, it could potentially overcome these 
biometric security controls, which may allow unauthorised access to accounts or sensitive personal data (Murphy, 2024). This is 
particularly troubling as our country becomes more digitalised and we are pressured by the government and companies to upload our personal 
data into their database. With little improvement in the cybersecurity infrastructure in Malaysia, it will likely only be a matter of time 
before our personal data is compromised.

### Comparisons with Global Cybersecurity Standards

If we compare Malaysia's level of cybersecurity with the best-class nations such as the European Union (EU) and the United States of 
America (USA), we can feel that Malaysia's level of cybersecurity has yet to reach its full potential. For starters, looking at Malaysia's 
new Cyber Security Act 2024 (CSA) and how it contrasts with the EU Cybersecurity Act, the two acts are cybersecurity-focused in each of 
their countries, most notably the codes of practice, risk assessments, and incident notification. Malaysia, while focusing on protection 
for the National Critical Information Infrastructure (NCII), has the EU focusing on larger critical sectors, digital services, and product 
security across the union. The most significant aspect is that the EU has wider regulation because it deals with organisations offering 
services to EU citizens, unlike Malaysia's CSA, which is solely for NCII organisations (European Commission, 2025).

Further research on the National Cyber Security Agency (NACSA) of Malaysia can be compared to the Cybersecurity and Infrastructure Security
Agency (CISA) of the US. NACSA operates with enforcement and regulatory powers and, by law, under the CSA 2024. One of the examples of 
their mandate is the introduction of a license to registered cybersecurity service providers. CISA, on the other hand, is working under the 
CISA Act of 2018 and several presidential decrees. CISA have an emphasis on providing directives and services as opposed to enforcing 
strict rules, as compared to NACSA (Flashpoint, 2023). Both agencies are attempting to defend, administer, and risk manage their respective
cyber infrastructure. However, NASCA is more centralised with required compliance and enforcement for NCII entities, whereas CISA appears 
to be focusing on cooperative effort with both the public and private sector partners in attempting to establish their own country's 
security. 

## SOCIETAL IMPLICATIONS OF DEEPFAKE PROLIFERATION

### How Deepfakes Contribute to Misinformation and Its Effects on Public Trust

Deepfake technology has been contributing to misinformation in our society by exploiting people's bias toward visual evidence, even when 
the evidence is fabricated (Popa & Cârlan, 2024). For decades, it has been common for people to consider video and audio recordings as 
indisputable evidence, as these have been hard to fabricate in the past. However, as deepfake technology improves and develops, it has 
contributed to the believability and spread of misinformation. Multiple studies have found that deepfake technology can be used to create 
misinformation to purposefully deceive the public, and can make it difficult for the public to detect and debunk misinformation (Vaccari & 
Chadwick, 2020). There have been many examples of malicious users using deepfake technology to destroy reputations, manipulate public 
opinion, and erode democratic processes (Lenaerts-Bergmans, 2025).

Studies have shown that deepfakes have embedded into the public distrust of digital content and news (Vaccari & Chadwick, 2020). Prolonged
exposure to deepfakes can often lead to confusion, uncertainty, and decreased faith in digital content. Even if people are not directly 
deceived by deepfake technology, the knowledge and awareness of it can ruin confidence in authentic content. Given the trend towards fake
news and misinformation on the Internet, people would be more prone to dismiss real evidence as fake; this phenomenon is also known as the
"liar's dividend" (Twomey et al., 2023). This distrust would eventually extend beyond just digital content and even more to other 
organisations, meaning it would be difficult for the public to maintain trust in official accounts or trusted media.

### Privacy Issues and Potential Legal Ramifications

Deepfake technology has raised a lot of concern around privacy that we usually do not think about, such as non-consensual impersonation and
identity theft. Deepfakes technology can be exploited to impersonate individuals without consent, severely breaching their privacy (Huang,
2024). These unauthorised uses of another person's identity could create concern and fear of harm to their reputation. Their fear is 
understandable because deepfake technology could deceive people into believing that someone has said or done something that they did not.
One common example is a malicious user using this technology to upload indecent content of another person online, ruining their reputation
in both the digital world and the real world. In addition, scammers use this technology to trick someone into transferring money on their 
behalf.

While Malaysia has no specific legislation addressing the problem of the malicious usage of deepfake technology, these uses could fall 
under the improper use of network facilities according to other laws in Malaysia, such as the Communications and Multimedia Act 1998 (CMA), 
the Penal Code and the Personal Data Protection Act 2010 (PDPA). A malicious deepfake technology user could be charged with Section 211(1) 
and Section 233 of the CMA, which relates to distributing inappropriate and inaccurate content online, with the intent to annoy, threaten 
or harass any person (Ahmad et al., 2018). It is also plausible they could be charged with defamation or cheating by pretending to be 
another person under Section 416 of the Penal Code. Lastly, provisions of the PDPA could be used to fight the collection and disclosure of 
personal data to third parties without notice to or consent of the data subject.

### Reputational Damage Caused by Deepfakes to Individuals and Organizations

One of the other consequential impacts of deepfake technology, which most people would discuss, is reputational harm to individuals and 
organisations. First and foremost, deepfake technology can harm the reputation of individuals through the creation and spreading of false 
narratives that can destroy their lives, personally and professionally. For example, some malicious users can create non-consensual 
deepfake content, particularly indecent content of another person, which makes up for 96% of deepfake content, which can lead to 
reputational damage (Fortinet, Inc., n.d.). These indecent contents can also be used to blackmail, either for ransom money or other favours
from individuals. In most cases, the victims comply with the demands because they do not want the fake indecent content released.

For businesses and other organisations, deepfake technology can be weaponised against them, which could lead to widespread reputational 
damage, financial losses, and a breakdown of trust with stakeholders and customers. In one survey, 67% of consumers would only purchase 
from brands that they deemed reputable (GAFA, 2025). Deepfake technology can be misused to produce false social media posts or videos of 
executives making controversial or unethical remarks, or behaving inappropriately around employees (Proofpoint, Inc., n.d.). Such deepfake 
scandals not only ruin a company's brand quickly but also erode public trust, which takes years to build. Once these trusts are eroded, it 
is costly and time-consuming to rebuild. Additionally, it is possible that deepfake technology could be misused for financial fraud. For 
example, a deepfake video or audio recording of executives could be used to instruct employees to commit financial fraud. A notable case 
involved a company in China where a deepfake voice of a CEO was used to authorise a fraudulent financial transfer, resulting in a loss of 
€220,000 in 2020 (Callan, 2022).

## REGULATORY FRAMEWORK GOVERNING DEEPFAKES IN MALAYSIA

### Malaysian Communications and Multimedia Commission (MCMC) Guidelines

The Malaysian Communications and Multimedia Commission (MCMC) has introduced a new guideline or code of conduct that requires internet 
messaging and social media companies to adopt several significant safety measures, such as user safety measures, child protection protocol,
risk assessments, and accountability practices (Mustaqim & Tasnima, n.d.). A major goal of the guideline is managing harmful content, which
would include scams, hate speech and manipulated media like deepfakes. 

These guidelines first centre on user safety measures, particularly children's safety. In order to promote user safety, service providers 
must identify and remove harmful content. This includes establishing and regularly reviewing a robust system for detecting harmful content.
They must also be able to set clear and transparent guidelines and processes for reporting, with 24 hours to take down harmful content. Moreover, age verification must be added to prevent children from accessing harmful content. Parental controls are expected to allow 
parents to monitor their child's online activity. These requirements created a safer environment for young users and educated them on safe 
digital practices.

In addition, service providers must actively monitor and address risks on their platforms. This guideline promotes partnerships with 
regulatory and law enforcement to reduce risks. They are also mandated by Malaysian Law to maintain thorough records of harmful content 
removals. Lastly, these service providers are required to submit reports twice a year to MCMC on their platform risk assessments and safety 
measures, and one public report every year on their practices to promote online safety.

### Penal Code Provisions Regarding Fraud and Impersonation
Malicious users who exploit deepfake technology may be subjected to prosecution for impersonation, fraud or defamation in accordance with 
the Malaysian Penal Code. In the earlier example, if deepfake content is used to impersonate someone to commit a fraudulent act, such as 
influencing someone to transfer money, the offender can be charged with Sections 415, 416 and 420 under the Penal Code. These sections 
discussed fraud, cheating by pretending to be another person, and knowingly substituting one person for another to deceive. The deepfake 
technology can serve a purpose for deception and personation under these sections. If the offender was found guilty, they could face 
sentences of more than one year imprisonment and whipping.

Those offenders could also find themselves charged with Section 499 of the Penal Code. Section 499 relates to defamation of character, 
which includes any act in which someone directly or indirectly intends to harm another person's reputation by means of publishing, writing,
or speaking. The act of creating and distributing a deepfake video or image that makes a false statement about someone may cause harm to 
their name and reputation and can be considered a defamatory act. For more serious cases, such as if the offender has gone so far as to 
blackmail or intimidate someone with deepfake technology, the offender may be charged with criminal intimidation under Section 503. The 
penalties for criminal intimidation are imprisonment for up to two years for less severe threats. However, the penalty can be increased to
seven years if the threat involves death or arson.

### Effectiveness of the Personal Data Protection Act (PDPA)

The Personal Data Protection Act (PDPA), introduced in 2010, has made solid progress in terms of protecting personal data. While it sets up 
a legal framework, it lacks effectiveness due to its narrow scope and specific exemptions. The PDPA outline principles that oversee how 
companies should treat their customers' personal data (Khye Yen, 2024). It required companies to obtain consent for personal data 
processing and provide them with a written notice. It also prohibits companies from disclosing personal data without consent and requires 
them to take practical steps to protect the data. Most importantly, these data are not retained for longer than needed, and it is the task
of the company to ensure the accuracy and integrity of the data. Failure to comply with these principles may result in legal penalties, 
including fines and imprisonment. It has made companies more conscious about how they handle data.

However, it should be noted that the PDPA regulatory framework still presents gaps and concerns. A significant limitation is that the PDPA
does not apply to the federal and state governments, which contradicts the objective of the PDPA to protect personal data. A prime example 
of this is the MySPR data breach incident in 2022, where the personal information of 22 million voters was leaked and sold illegally (Kai
Xin, 2025). This shows that PDPA should apply to agencies of the government to better protect the personal data of Internet users. 
Moreover, the PDPA applies only when commercial transactions occur. This means that a range of non-commercial situations, such as those 
carried out by political parties, non-profit organisations, and social clubs, are not covered by PDPA protections either. This narrow 
definition of commerciality means data is vulnerable in several situations outside of the commerciality of buying or selling goods and 
services. 

## STRATEGIC PROTECTION MEASURES FOR ORGANIZATIONS

### Advanced Cybersecurity Protocols for Organization

As cyber threats such as deepfake technology become more advanced, organisations are advised to use more advanced cybersecurity protocols 
that are more adaptive and proactive to protect their digital assets. First of all, organisations should adapt to zero trust architecture 
(ZTA), where the organisation operates on the premise of "never trust, always verify". ZTA uses the principle of treating every user as a 
potential threat. Therefore, it identifies and authorises every user request, no matter how harmless it seems. Organisations can also 
implement a micro-segmentation network where the network is broken down into smaller, isolated segments. In doing so, every user has access 
to the least amount of access necessary to do their work. This meant that every user accessing the organisation's network is limited in 
what they can access and what they cannot, even if one of the segments is breached, sensitive data cannot leak (Rose et al., 2020). This 
could minimise the attack surface area and reduce potential damage from a compromised account.

Moreover, organisations are advised to move away from a username and password and start using multi-factor authentication (MFA). MFA is an 
authentication method in which a user is required to provide two or more verification factors to gain access. Organisations can enforce MFA 
through methods such as hardware security keys (FIDO2) or a biometric authentication option (OneLogin, n.d.). In addition, MFA can be more 
adaptive and dynamically adjust the level of authentication required based on the access being requested. For example, a new login from an 
unfamiliar location or an unusual device should trigger an extra authentication step. It is important to transition to a passwordless 
system to reduce the risk of password-related attacks, such as brute-force attacks. However, it is important to note that no advanced 
cybersecurity protocols are perfect, and they should be reviewed from time to time.

### Importance of Employee Training and Cybersecurity Awareness Culture

Employee training is another avenue that an organisation can use to help protect itself from the misuse of deepfake technology. Training 
staff in cybersecurity awareness and preparedness would require an organisation to make sure that staff can identify and report suspicious
behaviour. Employees need to be educated on what deepfake technology is, how to identify deepfakes, and what steps to take when they 
suspect a deepfake. There are many different ways training can be offered to employees. Rather than traditional training in the classroom 
which can be boring, the organisation can have interactive online training, which staff can complete at a time according to their schedule 
and at their own speed. Organisations can also do workshops and seminars to provide hands-on training in detecting deepfakes (Byrd, 2024).

Employee training alone is not enough, it needs to be supported by a culture of security and safety within the organisation. An 
organisation's culture should encourage employees to ask questions and report issues without an added sense of blame or burden on the 
investigation process. Companies can also acknowledge employees who are proactive in identifying a deepfake. This feedback can reinforce 
and provide positive feedback that promotes a safer environment. Most importantly, leaders and managers need to model safe use of the 
internet. If leadership is modelling good security practices and communicating the importance of these practices to the team, employees are 
more likely to take cybersecurity seriously. Training is not a one-off event, it is an ongoing process. Cyber threats are rapidly evolving
therefore, organisations' training development will also need to continuously evolve.

### Robust Monitoring and Detection System

Technical and non-technical combinations support robust deepfake monitoring and detection systems. Certain deepfakes images reveal clear 
spatial and visual inconsistencies, like differences in colours between the altered and unaltered areas of the image. Video and audio 
deepfake threats can sometimes be detected by detecting a mismatch between speech-to-mouth movements. AI-based detectors, which can rapidly 
analyse videos and audio for inconsistencies, can be used in an organisation. These detector works well because they improve over time just 
like deepfake technology (Lenaerts-Bergmans, 2025).

Nevertheless, with deepfakes becoming more common and realistic becoming more difficult to detect as media becomes increasingly prevalent,
they can struggle to keep up with emerging generative AI techniques used to create deepfakes. Alternatively, you can also focus on 
detecting deepfakes by investigating intrinsic properties of the media file itself. You can analyse and review the metadata of the content,
which is information that describes, validates, or adds context about the content (Swatton & Leblanc, 2024). Discrepancies in creation 
dates, device information, or editing history can be a sign of manipulation and usage of deepfake technology.

Another procedure to detect deepfakes is through their distribution channels. For example, deepfakes that are produced for malicious 
purposes can often be found on social media being circulated by bot or troll accounts. These online accounts can be partially detected 
through the behaviour of the account, and so at this point, you aren’t detecting the deepfakes directly. Other ways that malicious users
love to pass deepfakes around are spam mail and links of dubious nature.

## CONCLUSION

### Key Findings and Insights

According to this report, we have found that deepfake technology has been continually improving since the emergence of generative AI. This 
technology has been misused to spread misinformation, violate the privacy of individuals, and cause damage to communities. As a result, 
individuals and organisations need to review and update their ways of using the Internet. Malaysia also needs to update its cybersecurity
law, which includes the Malaysian Communications and Multimedia Commission (MCMC), the Penal Code, and the Malaysian Personal Data 
Protection Act (PDPA), to catch up with the emergence of deepfake technology. Furthermore, our cybersecurity awareness needs to be 
improved, and we should start using more advanced cybersecurity protocols and a robust detection system to prevent ourselves from becoming
victims of deepfakes.

### Importance of Proactive Measures in Addressing Emerging Cybersecurity Challenges
From the report, we have found that deepfake technology can contribute to the mass spread of misinformation, having potential legal and 
privacy issues, and could cause irreparable reputational damage to individuals and organisations. Thus, it is important to take proactive 
measures to prevent falling victim to a scam involving deepfake technology. Some proactive measures individuals and organisations can take 
are to adapt to a trust architecture and start using multi-factor authentication. Individuals and organisations also need to improve their 
cybersecurity awareness. A robust monitoring and detection system also needs to be utilised to lower the number of deepfake scams on the 
Internet.  

## REFERENCES

- Agarwal, S., Peta, S., & Panyam, S. (2024). Deepfakes in Healthcare: Reviewing the transformation potential and its challenges. International Journal of Intelligent Systems and Applications in Engineering, 12(4), 3965–3970. https://ijisae.org/index.php/IJISAE/article/view/6956
- Ahmad, R., Aziz, A. S. A., & Noor, N. a. M. (2018). Restrictive Provisions of the Communications and Multimedia Act 1998: A discussion. The European Proceedings of Social & Behavioural Sciences, 834–840. https://doi.org/10.15405/epsbs.2018.12.03.85
- BERNAMA. (2025, January 3). MCMC expanding awareness on online safety. https://www.bernama.com/en/news.php?id=2397879
- Byrd, P. (2024, September 26). Deepfake Awareness Training: A Complete Guide. Hook Security. https://www.hooksecurity.co/blog/deepfake-awareness-training
- Callan, T. (2022, February 24). What deepfakes mean for cybersecurity. Sectigo® Official. https://www.sectigo.com/resource-library/what-deepfakes-mean-for-security
- Chan, C. (2024). Cyber Security Act 2024: A New era for Cybersecurity in Malaysia. PwC Malaysia. https://www.pwc.com/my/en/assets/publications/2024/pwc-my-cyber-security-act-2024-new-era-for-cybersecurity-in-malaysia.pdf
- European Commission. (2025, July 9). EU Cybersecurity Act | Shaping Europe’s Digital Future. https://digital-strategy.ec.europa.eu/en/policies/cybersecurity-act
- Flashpoint. (2023, September 22). Cybersecurity and Infrastructure Security Agency (CISA). https://www.flashpoint.io/intelligence-101/cisa
- Fortinet, Inc. (n.d.). What is deepfake: AI endangering your cybersecurity? https://www.fortinet.com/resources/cyberglossary/deepfake
- GAFA. (2025, August 13). Deepfakes in 2024–25: Escalating risks for businesses. https://gafa.org.in/deepfake-fraud-case-studies-2025/
- Glick, J. (2023). Deepfake Satire and the Possibilities of Synthetic Media. Afterimage, 50(3), 81–107. https://doi.org/10.1525/aft.2023.50.3.81
- Howard, K., Holliday, L., & Sharma, S. (Directors). (2020). Science & Tech Spotlight: DeepFakes. In C. Mai, A. Brooks, A. McMillon, & B. Shouse (Eds.), GAO | Science, Technology Assessment, and Analytics (GAO-20-379SP). U.S. Government Accountability Office (GAO). https://www.gao.gov/assets/gao-20-379sp.pdf
- Huang, K. (2024, June 25). AI deepfake security concerns. CSA. https://cloudsecurityalliance.org/blog/2024/06/25/ai-deepfake-security-concerns
- Kai Xin, T. (2025, May 6). Malaysia’s Personal Data Protection Act (PDPA): Is it effective enough. Record of Law. https://recordoflaw.in/malaysias-personal-data-protection-act-pdpa-is-it-effective-enough/
- Khye Yen, L. (2024, November 14). Recent developments in Malaysia’s Personal Data Protection Act. HHQ. https://hhq.com.my/posts/recent-developments-in-malaysias-personal-data-protection-act
- Lenaerts-Bergmans, B. (2025, January 16). What is a Deepfake Attack? CrowdStrike. https://www.crowdstrike.com/en-us/cybersecurity-101/social-engineering/deepfake-attack
- Murphy, J. (2024, June 17). How deepfakes threaten biometric security controls. Search Security. https://www.techtarget.com/searchsecurity/tip/How-deepfakes-threaten-biometric-security-controls
- Mustaqim, A., & Tasnima, W. (n.d.). Code of Conduct (Best Practice) for Internet Messaging Service Providers and Social Media Service Providers in Malaysia. https://nzchambers.com/code-of-conduct-best-practice-for-internet-messaging-service-providers-and-social-media-service-providers-in-malaysia/#_ftn3
- OneLogin. (n.d.). What is Multi-Factor Authentication (MFA)? https://www.onelogin.com/learn/what-is-mfa
- Popa, E. O., & Cârlan, A. I. (2024). Evidentiary convincing and evidentiary fallacies. Argumentation, 38(3), 349–367. https://doi.org/10.1007/s10503-024-09630-3
- Proofpoint, Inc. (n.d.). What is a deepfake? Definition & technology. https://www.proofpoint.com/us/threat-reference/deepfake
- Rose, S., Borchert, O., Mitchell, S., & Connelly, S. (2020). Zero Trust Architecture. https://doi.org/10.6028/nist.sp.800-207
- Swatton, P., & Leblanc, M. (2024, June 7). What are deepfakes and how can we detect them? The Alan Turing Institute. https://www.turing.ac.uk/blog/what-are-deepfakes-and-how-can-we-detect-them
- Twomey, J., Ching, D., Aylett, M. P., Quayle, M., Linehan, C., & Murphy, G. (2023). Do deepfake videos undermine our epistemic trust? A thematic analysis of tweets that discuss deepfakes in the Russian invasion of Ukraine. PLoS ONE, 18(10), e0291668. https://doi.org/10.1371/journal.pone.0291668
- Vaccari, C., & Chadwick, A. (2020). Deepfakes and Disinformation: Exploring the Impact of Synthetic Political Video on Deception, Uncertainty, and Trust in News. Social Media + Society, 6(1). https://doi.org/10.1177/2056305120903408
