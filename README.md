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

#### Proximity Sensing for Contact Tracing [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/proximity-sensing-for-contact-tracing.pdf)

- The TC4TL challenge is aimed towards designing an
effective proximity sensing algorithm that can accurately provide
exposure notifications. In this work, we describe our approach
to model sensor and other device level data to estimate distance
between the two phones. We also present our research and data
analysis on the TC4TL challenge dataset and discuss various
limitations associated with the task as well as dataset.
 
 
#### DAMS: Meta-Estimation of Private Sketch Data Structures for Differentially Private COVID-19 Contact Tracing [LINK](https://github.com/vepakom/PrivacyDocuments/blob/master/DAMS_Meta-estimation_of_private_sketch_data_structures_for_differentially_private_contact_tracing.pdf)

- We propose an improved private count-mean-sketch data structure and show its applicability to differentially private contact tracing. Our proposed scheme (Diversifed Averaging for Meta estimation of Sketches-DAMS) provides a better trade-off between true positive rates and false positive rates while maintaining differential privacy (a widely accepted formal standard for privacy).We show its relevance to the social good application of private digital contact tracing for COVID- 19 and beyond. The scheme involves one way locally differentially private uploads from the infected client devices to a server that upon a post-processing obtains a private aggregated histogram of locations traversed by all the infected clients within a time period of interest. The private aggregated histogram is then downloaded by any querying client in order to compare it with its own data on-device, to determine whether it has come into close proximity of any infected client or not. We present empirical experiments that show a substantial improvement in performance for this particular application. We also prove theoretical variance-reduction guarantees of the estimates obtained through our scheme and verify these findings via experiments as well.


#### Proximity Inference with Wifi-Colocation during the COVID-19 Pandemic [LINK](https://github.com/PrivateKit/PrivacyDocuments/blob/master/Wifi_colocation%20(1).pdf)

- In this work we propose using WiFi signals recorded on the phone for performing digital contact tracing. The approach works by scanning the access point information on the device and storing it for future purposes of privacy preserving digital contact tracing. We make our approach resilient to different practical scenarios by configuring a device to turn into hotspot if the access points are unavailable. This makes our proposed approach to be feasible in both dense urban areas as well as sparse rural places. We compare and discuss various shortcomings and advantages of this work over other conventional ways of doing digital contact tracing. Preliminaries results indicate the feasibility and efficacy of our approach for the task of proximity sensing which could be relevant and accurate for its relevance to contact tracing and exposure notifications.
