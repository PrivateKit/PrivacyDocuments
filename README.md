# PrivacyDocuments
Repository for Privacy Research done by the Safe Paths community. The repository is maintained by [Abhishek](https://github.com/tremblerz) and [Mikhail](https://github.com/mikhaildmitrienko). Please make a pull request or reach out to them if you want to get a paper added.

For more privacy and contact tracing research and whitepapers visit [Covid Safe Paths Website](http://covidsafepaths.org/) and [Split Learning Research](https://splitlearning.github.io/)

#### Adding Location Context to Apple/Google Exposure Notification Bluetooth API: MIT SafePaths Encryption Proposals for GPS + Bluetooth [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/LocationContext.pdf)
 - Contact tracing requires a strong understanding of location and context of the infection encounters. Although Bluetooth technology does not provide location or context of the encounters, we present key privacy preserving ideas to capture this context that can be used in or alongside the forthcoming Google/Apple Bluetooth Exposure Notification API (GAEN).

#### SafePaths Privacy Preserving WiFi Co-location [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/WiFiPrivacy.pdf)
 - Estimate whether two devices are close to each other (and the distance between them) while maintaining privacy using WiFi protocols. We want to achieve co-location under two constraints (i) privacy (ii) no crowdsourced pre-recorded SSID/Mac addresses for signal strength or Mac address mapping to GPS locations.


#### Privacy Guidelines for Contact Tracing Applications [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/PrivacyGuideline.pdf)
 - Contact tracing is a very powerful method to implement and enforce social distancing to avoid spreadingof infectious diseases. The traditional approach of contact tracing is time consuming, manpower intensive, dangerousand prone to error due to fatigue or lack of skill. In this work we discuss the various scenarios which a contact tracing application should be able to handle. Wehighlight the privacy handling of some of the prominent contact tracing applications. Additionally, we describe thevarious threat actors who can disrupt its working, or misuse end user’s data, or hamper its mass adoption. Finally,we present privacy guidelines for contact tracing applications from different stakeholder’s perspective.

#### Bluetooth based Proximity, Multi-hop Analysis and Bi-directional Trust: Epidemics and More [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/ContactTracingBeyondBluetooth.pdf)
 - In this paper, we propose a trust layer on top of Bluetooth and similar wireless communication
technologies that can form mesh networks. This layer as a protocol enables computing trust scores based
on proximity and bi-directional transfer of messages in multiple hops across a network of mobile devices.
We describe factors and an approach for determining these trust scores and highlight its applications
during epidemics such as COVID-19 through improved contact-tracing, better privacy and verification
for sensitive data sharing in the numerous Bluetooth and GPS based mobile applications that are being
developed to track the spread.

#### Contact Tracing: Holistic Solution beyond Bluetooth [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/ContactTracingBeyondBluetooth.pdf)
 - Contact tracing is a critical part of reopening society. While manual contact tracing by medical professionals is
essential, there’s growing acknowledgement that supplementing this with digital approaches might make a
significant difference in the speed with which we can reopen. In this paper, we’ll compare some of the existing technologies that can be used to aid contact tracing and
exposure notification efforts, and make the case for using a holistic, multi-modal approach rather than relying
exclusively on a single technology.

#### TRANSPARENCY AND CONSENT - BY DEFAULT [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/TransparencyConsent.pdf)
 - Difficult times lead to clear perspectives. The coronavirus (COVID-19) pandemic has stopped “life as normal” across
much of the world. As governments and healthcare systems put into place strict measures around movement to
slow the rate of infection and minimise the death toll, we are coming into a period of significant citizen
uncertainty. Managing the outbreak of COVID-19 and flattening the curve is now a global challenge. We read about contact tracing a patient in Korea, Patient 31, a woman who went to the hospital after a car
accident, went to a hotel buffet, attended a church, came back to the hospital, and in turn ended up impacting
more than a thousand people. The health authorities and contact tracers had to painstakingly interview more than
a thousand people to back-trace and see who could be at risk to avoid further spread.

#### Private GPS Intersection [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/GpsEncryption.pdf)
 - Exposure notification in GPS based contact tracing platform requires performing intersection of at least two GPS trails, however, these GPS trails are sensitive information about a user and hence requires performing intersection in a private manner. Low entropy in the GPS trails makes this problem even more challenging as brute force becomes feasible. In this paper, we propose methods and system design for performing private GPS trail intersection using secure cryptographic methods. We also highlight potential attacks which can be performed on the proposed techniques.
 
#### COVID-19 Contact-Tracing Mobile Apps: Evaluation And Assessment For Decision Makers [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/apps-evaluation.pdf)
 - More than 150,000 deaths are now attributed to the global COVID-19 pandemic. Many thousands more lives are expected to be lost before we have brought the disease under control and are capable of managing future spikes in the number of cases. In an effort to both slow and stop the disease, communities across the world have halted everyday life, requesting or requiring their residents to close non-essential businesses, stop going to school, and stay home. Digital initiatives hope to support safe and wellconsidered approaches to the reopening of our societies while simultaneously reducing the human loss of life by giving frontline officials modern tools with
which to control this pandemic.
   One particular set of modern digital tools aims to upgrade contact-tracing capacity, typically a lengthy and laborious process. In addition to increasing the speed with which contact-tracers can reach those who have been exposed to the disease, these tools can increase the accuracy of contact tracing. However, many first-generation digital contact-tracing tools have paved the way for a post-pandemic surveillance state and the mistreatment of private, personal information. Privacy must remain at the forefront of the global response, lest short-term pandemic interventions enable long-term surveillance and abuse. The design and development of the next generation of contact-tracing tools offers an opportunity to sharply pivot to solutions using privacy-first principles and collaborative, open-source designs. These tools present an opportunity to save lives by flattening the curve of the pandemic and to provide ecoonomic relief without allowing privacy infringements now or in the future

#### The Architecture of Trust in Contact Tracing [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/evaluating-contact-tracing-apps.pdf)
 - If you had to choose between safety and privacy, what would you choose? If you had to choose between your source of income and your individual rights, which would win out? These are no longer hypotheticals; across the world, governments and individuals are being forced to make these decisions.

#### Contact Tracing to Manage COVID19 Spread – Balancing Personal Privacy and Public Health [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/contact-tracing-public-health.pdf)
 - Given promise of digital solutions to mitigate disease spread, it is critical the science of contact tracing be explored, particularly given their cost-efficiency and scalability. It is feasible to manage privacy and public good by innovating appropriate solutions for how data is aggregated and users are informed of exposures. However, potential benefit to address waves of the current pandemic or future outbreaks can’t be under-stated.
 
 #### Comparing Manual Contact Tracing and Digital Contact Advice [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/comparing_tracing.pdf)
 
 - Manual contact tracing is a top-down solution that starts with contact tracers at the public health
level, who identify the contacts of infected individuals, interview them to get additional context
about the exposure, and also monitor their symptoms and support them until the incubation period
is past. On the other hand, digital contact tracing is a bottom-up solution that starts with citizens
who on obtaining a notification about possible exposure to an infected individual may choose to
ignore the notification, get tested to determine if they were actually exposed or self-isolate and
monitor their symptoms over the next two weeks. Most expertsrecommend a combination of manual
contact tracing and digital contact advice but they are not based on a scientific basis. For example, a
possible hybrid solution could involve a smartphone based alert that requests the possible contact of
an infected individual to call the Public Health (PH) number for next steps, or in some cases, suggest
ways to self-assess in order to reduce the burden on PH so only most critical cases require a phone
conversation. In this paper, we aim to compare the manual and digital approaches to contact tracing
and provide suggestions for potential hybrid solutions.

#### PPContactTracing: A Privacy-Preserving Contact Tracing Protocol for COVID-19 Pandemic [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/ppcontacttracing.pdf)

- Several contact tracing solutions have been proposed
and implemented all around the globe to combat the spread of
COVID-19 pandemic. But, most of these solutions endanger the
privacy rights of the individuals and hinder their widespread
adoption. We propose a privacy-preserving contact tracing protocol for the efficient tracing of the spread of the global pandemic.
It is based on the private set intersection (PSI) protocol and
utilizes the homomorphic properties to preserve the privacy at
the individual level. A hierarchical model for the representation
of landscapes and rate-limiting factor on the number of queries
have been adopted to maintain the efficiency of the protocol.

#### Proximity Sensing: Modeling and Understanding Noisy RSSI-BLE Signals and Other Mobile Sensor Data for Digital Contact Tracing [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/ProximitySensingForContactTracing.pdf)

- As we await a vaccine, social-distancing via efficient contact tracing has emerged as the primary health strategy to dampen the spread of COVID-19. To enable efficient digital contact tracing, we present a novel system to estimate pair-wise individual proximity, via a joint model of Bluetooth Low Energy (BLE) signals with other on-device sensors (accelerometer, magnetometer, gyroscope). We explore multiple ways of interpreting the sensor data stream (time-series, histogram, etc) and use several statistical and deep learning methods to learn representations for sensing proximity. We report the normalized Decision Cost Function (nDCF) metric and analyze the differential impact of the various input signals, as well as discuss various challenges associated with this task.
 
 
#### DAMS: Meta-Estimation of Private Sketch Data Structures for Differentially Private COVID-19 Contact Tracing [LINK](https://github.com/vepakom/PrivacyDocuments/blob/master/DAMS_Meta-estimation_of_private_sketch_data_structures_for_differentially_private_contact_tracing.pdf)

- We propose an improved private count-mean-sketch data structure and show its applicability to differentially private contact tracing. Our proposed scheme (Diversifed Averaging for Meta estimation of Sketches-DAMS) provides a better trade-off between true positive rates and false positive rates while maintaining differential privacy (a widely accepted formal standard for privacy).We show its relevance to the social good application of private digital contact tracing for COVID- 19 and beyond. The scheme involves one way locally differentially private uploads from the infected client devices to a server that upon a post-processing obtains a private aggregated histogram of locations traversed by all the infected clients within a time period of interest. The private aggregated histogram is then downloaded by any querying client in order to compare it with its own data on-device, to determine whether it has come into close proximity of any infected client or not. We present empirical experiments that show a substantial improvement in performance for this particular application. We also prove theoretical variance-reduction guarantees of the estimates obtained through our scheme and verify these findings via experiments as well.


#### Proximity Inference with Wifi-Colocation during the COVID-19 Pandemic [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/Wifi_colocation%20(1).pdf)

- In this work we propose using WiFi signals recorded on the phone for performing digital contact tracing. The approach works by scanning the access point information on the device and storing it for future purposes of privacy preserving digital contact tracing. We make our approach resilient to different practical scenarios by configuring a device to turn into hotspot if the access points are unavailable. This makes our proposed approach to be feasible in both dense urban areas as well as sparse rural places. We compare and discuss various shortcomings and advantages of this work over other conventional ways of doing digital contact tracing. Preliminaries results indicate the feasibility and efficacy of our approach for the task of proximity sensing which could be relevant and accurate for its relevance to contact tracing and exposure notifications.

#### DISCO: Dynamic and Invariant Sensitive Channel Obfuscation for Deep Neural Networks [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/DISCO.pdf)

- Recent deep learning models have shown remarkable
performance in image classification. While these deep
learning systems are getting closer to practical deployment,
the common assumption made about data is that it does
not carry any sensitive information. This assumption may
not hold for many practical cases, especially in the domain
where an individual’s personal information is involved, like
healthcare and facial recognition systems. We posit that selectively
removing features in this latent space can protect
the sensitive information and provide better privacy-utility
trade-off. Consequently, we propose DISCO which learns a
dynamic and data driven pruning filter to selectively obfuscate
sensitive information in the feature space. We propose
diverse attack schemes for sensitive inputs & attributes and
demonstrate the effectiveness of DISCO against state-ofthe-
art methods through quantitative and qualitative evaluation.
Finally, we also release an evaluation benchmark
dataset of 1 million sensitive representations to encourage
rigorous exploration of novel attack schemes.

#### Challenges of Equitable Vaccine Distribution in the COVID-19 Pandemic [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/challenges_equitable.pdf)

- As several COVID-19 vaccine candidates approach approval for human use,
governments around the world are preparing comprehensive standards for vaccine
distribution and monitoring to avoid long-term consequences that may result
from rush-to-market. In this early draft article, we identify challenges for vaccine
distribution in four core areas - logistics, health outcomes, user-centric impact,
and communication. Each of these challenges is analyzed against five critical
consequences impacting disease-spread, individual behaviour, society, the
economy, and data privacy. Disparities in equitable distribution, vaccine efficacy,
duration of immunity, multi-dose adherence, and privacy-focused record keeping
are among the most critical diculties that must be addressed. While many of
these challenges have been previously identied and planned for, some have not
been acknowledged from a comprehensive view to account for unprecedented
repercussions in specific subsets of the population.
The logistics of equitable, widespread vaccine distribution in disparate
populations and countries of various economic, racial, and cultural constitutions
requires careful planning and consideration for global vaccine success. We also
describe unique challenges regarding vaccine efficacy in specialized populations
including children, the elderly, and immunocompromised individuals
Furthermore, we report the potential for understudied drug-vaccine interactions
as well as the possibility that certain vaccine platforms may increase susceptibility
to HIV infection. Given these complicated issues, the importance of
privacy-focused, user-centric systems for vaccine education and incentivization
along with clear communication from governments, organizations, and academic
institutions is imperative. These challenges are by no means insurmountable, but
require thorough consideration to avoid consequences that span a range of
disease-related, individual, societal, economic, and security domains.

#### Clinical Landscape of COVID-19 Testing: Difficult Choices [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/clinical_landscapes.pdf)

- The coronavirus disease 2019 (COVID-19) pandemic
has spread rapidly across the world, leading to enormous
amounts of human death and economic loss. Until definitive
preventive or curative measures are developed, policies regarding
testing, contact tracing, and quarantine remain the best public
health tools for curbing viral spread. Testing is a crucial component
of these efforts, enabling the identification and isolation of
infected individuals. Differences in testing methodologies, time
frames, and outcomes can have an impact on their overall
efficiency, usability and efficacy. In this early draft, we draw
a comparison between the various types of diagnostic tests
including PCR, antigen, and home tests in relation to their
relative advantages, disadvantages, and use cases. We also look
into alternative and unconventional methods. Further, we analyze
the short-term and long-term impacts of the virus and its testing
on various verticals such as business, government laws, policies,
and healthcare.

#### Digital Landscape of COVID-19 Testing: Challenges and Opportunities [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/digital_landscape.pdf)

- The COVID-19 Pandemic has left a devastating trail all over the world, in terms
of loss of lives, economic decline, travel restrictions, trade deficit, and collapsing
economy including real-estate, job loss, loss of health benefits, the decline in
quality of access to care and services and overall quality of life. Immunization
from the anticipated vaccines will not be the stand-alone guideline that will help
surpass the pandemic and return to normalcy. Four pillars of effective public
health intervention include diagnostic testing for both asymptomatic and
symptomatic individuals, contact tracing, quarantine of individuals with
symptoms or who are exposed to COVID-19, and maintaining strict hygiene
standards at the individual and community level. Digital technology, currently
being used for COVID-19 testing include certain mobile apps, web dashboards,
and online self-assessment tools. Herein, we look into various digital solutions
adapted by communities across universities, businesses, and other organizations.
We summarize the challenges experienced using these tools in terms of quality of
information, privacy, and user-centric issues. Despite numerous digital solutions
available and being developed, many vary in terms of information being shared in
terms of both quality and quantity, which can be overwhelming to the users.
Understanding the testing landscape through a digital lens will give a clear
insight into the multiple challenges that we face including data privacy, cost, and
miscommunication. It is the destiny of digitalization to navigate testing for
COVID-19. Block-chain based systems can be used for privacy preservation and
ensuring ownership of the data to remain with the user. Another solution involves
having digital health passports with relevant and correct information. In this early
draft, we summarize the challenges and propose possible solutions to address the
same.

#### COVID-19 Outbreak Prediction and Analysis using Self Reported Symptoms [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/outbreak_prediction.pdf)

- The COVID-19 pandemic has challenged scientists and
policy-makers internationally to develop novel approaches to
public health policy. Furthermore, it has also been observed
that the prevalence and spread of COVID-19 varies across different
spatial, temporal and demographics. Despite ramping
up testing, we still are not at the required level in most parts
of the globe. Therefore, we utilize self-reported symptoms
survey data to understand trends in the spread of COVID-19. The aim of this study is to segment populations that are
highly susceptible. In order to understand such populations,
we perform exploratory data analysis, outbreak prediction,
and time-series forecasting using public health and policy
datasets. From our studies, we try to predict the likely % of
population that tested positive for COVID-19 based on selfreported
symptoms. Our findings reaffirm the predictive value
of symptoms, such as anosmia and ageusia. And we forecast
that the % of population having COVID-19-like illness (CLI)
and those tested positive as 0.15% and 1.14% absolute error
respectively. These findings could help aid faster development
of the public health policy, particularly in areas with
low levels of testing and having a greater reliance on selfreported
symptoms. Our analysis sheds light on identifying
clinical attributes of interest across different demographics.
We also provide insights into the effects of various policy enactments
on COVID-19 prevalence.

#### Verifiable Proof of Health using Public Key Cryptography [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/proof_of_health.pdf)

- In the current pandemic, testing continues to be the most important tool for monitoring and curbing
the disease spread and early identification of the disease to perform health-related interventions like
quarantine, contact tracing and etc. Therefore, the ability to verify the testing status is pertinent as
public places prepare to safely open. Recent advances in cryptographic tools have made it possible to
build a secure and resilient digital-id system. In this work, we propose to build an end to end COVID-19
results verification protocol that takes privacy, computation, and other practical concerns into account
for designing an inter-operable layer of testing results verification system that could potentially enable
less stringent and more selective lockdowns. We also discuss various concern encompassing the security,
privacy, ethics and equity aspect of the proposed system.

#### MIT SAFEPATHS CARD (MISACA): AUGMENTING PAPER BASED VACCINATION CARDS WITH PRINTED CODES [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/safepaths_card.pdf)

- In this early draft, we describe a user-centric, card-based system for vaccine distribution.
Our system makes use of digitally signed QR codes and their use for
phased vaccine distribution, vaccine administration/record-keeping, immunization
verification, and follow-up symptom reporting. Furthermore, we propose and
describe a complementary scanner app system to be used by vaccination clinics,
public health officials, and immunization verification parties to effectively utilize
card-based framework. We believe that the proposed system provides a privacypreserving
and efficient framework for vaccine distribution in both developed and
developing regions.

#### Spatial K-anonymity: A Privacy-preserving Method for COVID-19 Related Geo-spatial Technologies [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/spatial_k.pdf)

- There is a growing need for spatial privacy considerations in the many geo-spatial technologies that have been
created as solutions for COVID-19-related issues. Although effective geo-spatial technologies have already
been rolled out, most have significantly sacrificed privacy for utility. In this paper, we explore spatial kanonymity,
a privacy-preserving method that can address this unnecessary tradeoff by providing the best of
both privacy and utility. After evaluating its past implications in geo-spatial use cases, we propose applications
of spatial k-anonymity in the data sharing and managing of COVID-19 contact tracing technologies as well as
heat maps showing a user’s travel history. We then justify our propositions by comparing spatial k-anonymity
with several other spatial privacy methods, including differential privacy, geo-indistinguishability, and manual
consent based redaction. Our hope is to raise awareness of the ever-growing risks associated with spatial
privacy and how they can be solved with Spatial K-anonymity.

#### COVID-19 Tests Gone Rogue: Privacy, Efficacy, Mismanagement and Misunderstandings [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/tests_gone_rogue.pdf)

- COVID-19 testing, the cornerstone for effective screening and identification of
COVID-19 cases, remains paramount as an intervention tool to curb the spread
of COVID-19 both at local and national levels. However, the speed at which the
pandemic struck and the response was rolled out, the widespread impact on
healthcare infrastructure, the lack of sufficient preparation within the public
health system, and the complexity of the crisis led to utter confusion among test
takers. Invasion of privacy remains a crucial concern. The user experience of test
takers remains low. User friction affects the user behavior and discourages
participation in testing programs. Test efficacy has been overstated. Test results
are poorly understood resulting in inappropriate follow-up recommendations.
Herein, we review the current landscape of COVID-19 testing, identify four key
challenges, and discuss the consequences of the failure to address these
challenges.
The current infrastructure around testing and information propagation is highly
privacy invasive and does not leverage scalable digital components. In this work,
we discuss challenges complicating the existing covid-19 testing ecosystem and
highlight the need to improve the testing experience for the user and reduce
privacy invasions. Digital tools will play a critical role in resolving these
challenges.

