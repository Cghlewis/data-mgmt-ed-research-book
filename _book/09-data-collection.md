# Data Collection {#collect}

<div class="figure" style="text-align: center">
<img src="img/lifecycle_track.PNG" alt="Data collection in the research project life cycle" width="80%" />
<p class="caption">(\#fig:fig10-1)Data collection in the research project life cycle</p>
</div>

When collecting original data as part of your study (i.e., you are administering your own survey or assessment as opposed to using existing data), data management best practices should be interwoven throughout your data collection process. The number one way to ensure the integrity of your data is to spend time planning your data collection efforts. Not only does planning minimize errors, it also keeps your data secure, valid, and relieves future data cleaning headaches. 

If you have ever created a data collection instrument and expected it to export data that looks like the image on the left (Figure \@ref(fig:fig10-2)), but instead you export data that looks like the image on the right, then you know what I mean. Collecting quality data doesn't just happen because you create an instrument, it takes careful consideration, structure, and care on the part of the entire team.

<div class="figure" style="text-align: center">
<img src="img/bad_data_collect.PNG" alt="A comparison of data collected without planning and data collected with planning" width="100%" />
<p class="caption">(\#fig:fig10-2)A comparison of data collected without planning and data collected with planning</p>
</div>


## Quality assurance and control

In addition to planning data collection logistics (i.e. how will data be collected, who will collect it, and when), teams should spend time prior to data collection anticipating potential data integrity problems that may arise during data collection and putting procedures in place that will reduce those errors [@dime_analytics_data_2021; @northern_illinois_university_data_nodate]. As shown in Figure \@ref(fig:fig10-1), creating data collection instruments is typically a collaborative effort between the project management and data management team members. Even if the project management team builds the tools, the data management team is overseeing that the data collected from the tool aligns with expectations set in the data dictionary. In this chapter we will review two types of practices that both project management and data management team members can implement that will improve the integrity of your data.

1. Quality assurance practices that happen before data is collected
    - Best practices associated with designing and building your data collection instruments
2. Quality control practices implemented during data collection 
    - Best practices associated with managing and reviewing data during collection

Before we dive into collecting data, it's important to first review the ethical and legal considerations of your data collection effort. When working with human subjects it is likely that an Institutional Review Board (IRB) will need to review and approve all of your data collection instruments as well as any agreement forms that will be collected as part of your study. Our next section will provide an overview of the IRB and its requirements as well as best practices for creating agreement forms for participants and partners.

## Institutional Review Board

An IRB is a formal organization designated to review and monitor human participant research and ensure that the welfare, rights, and privacy of research participants are maintained throughout the project [@oregon_state_university_what_2012]. If you are conducting education research with human participants you will most likely have some interaction with and oversight from one or more IRBs. IRBs exist at institutions where research is conducted, including universities, school districts, state agencies, or research institutions, and in some industries such as clinical research, even independent IRBs are available for hire [@emanuel_should_2006]. Even within institutions there can be more than one IRB (e.g., a medical review board and a behavioral science review board) [@duru_institutional_2023]. Before reviewing potential requirements, let's review the history of this administrative body.

### Background

In 1974 the IRB was established as part of the National Research Act in response to a long history of unethical research that had been conducted with human participants [@qiao_brief_2018]. In 1979, the Belmont Report [@the_national_commission_for_the_protection_of_human_subjects_of_biomedical_and_behavioral_research_belmont_1979] outlined a set of ethical principles for doing research with human participants. Those ethical principles included the following [@duru_institutional_2023; @huisman_3_nodate]:

1. Respect for persons
    - This included both protecting autonomy of participants by acquiring consent as well as providing a plan to protect participant privacy
      - In practice this means acquiring consent in a way that ensures participants can comprehend what is being asked of them, ensuring that they understand that their participation is voluntary, and ensuring that they understand the plan to protect their privacy
2. Beneficence
    - This involved maximizing good and minimizing harm in the study, for both participants and society at large
      - In practice this means taking time to assess risk and benefits of your study for both the intervention itself as well as the data collection efforts (e.g., how burdensome is the survey)
3. Justice 
    - This included providing additional care and consideration when working with subjects who are vulnerable to coercion or undue influence (e.g., children, prisoners), as well as making sure practices are non-exploitative and that there is fair distribution of costs and benefits across all participants
      - In practice this involves fairness in the selection of participants

Heavily influenced by the Belmont Report, in 1991 the Federal Policy for the Protection of Human Subjects was published, establishing core procedures for human subject protections. The policy, 45 CFR part 46 [@office_for_human_research_protections_45_2016], included four subparts. Subpart A, known as the "Common Rule" for the 15 federal departments and agencies which codified the policy in separate regulations, provided a set of protections for human subjects research including informed consent, review by an IRB, and compliance monitoring [@national_institute_of_justice_common_2007; @office_for_human_research_federal_2009].

In 2018 the Common Rule was revised in order to better protect research participants and to reduce administrative burden [@office_for_human_research_office_for_human_research_revised_2018; @us_department_of_health_and_human_services_whats_nodate]. While many revisions were made, some changes that are applicable to education researchers include the following [@fordham_university_revised_nodate]:

- Revisions and additions to exempt categories, many of which are applicable to research conducted in educational settings 
- Reduced burden of continuing review, particularly for exempt and expedited studies
- Clarifications on how informed consent should be organized, written, and provided

### Requirements

While each institution's IRB submission process is different, typically if your study involves working with human subjects you are required to submit an application to an IRB. Before submitting your application you will need to determine what review category your study falls under as the application differs depending on the category [@lafayette_college_three_nodate; @northwestern_university_exempt_nodate; @university_of_california_berkeley_exempt_2022].

1. Exempt
    - These studies usually involve minimal risk and fit within categories predefined by your IRB (e.g., evaluating the use of accepted or revised standardized tests). These studies typically involve a shorter review process and a quicker review than non-exempt studies. 
2. Expedited
    - These studies also involve minimal risk but do not meet criteria for exempt status (e.g., collection of voice, video, or image data from non-vulnerable populations).
3. Full Review
    - If a study does not fall into one of the two categories above (e.g., collection of information about illegal behavior), it requires full review, discussed by the full board at a convened meeting.
    
In education research you are most often submitting your application to your institution's IRB. However, there are situations where that process might vary. For instance, in the case of multi-site or cooperative, non-exempt projects, it may be necessary to submit a single IRB (sIRB). In this situation, an authorization agreement is signed by collaborating institutions and one institution is designated as the IRB-of-Record. This institution then becomes the authority for review and continuing oversight of study activities [@cornell_research_services_multi-site_2019; @university_of_michigan_authorization_2023].

As part of your application, common documents you may be required to submit include the following [@cabrini_university_submissions_nodate; @duru_institutional_2023]:

1. Certificates from human subjects training (e.g., CITI training^[https://about.citiprogram.org/])
1. Research protocol (see Chapter \@ref(document))
    - When writing your protocol, make sure to review your IRB's rules around data handling and include this information in your plan. IRBs typically have specific rules for things such as how paper and electronic data must be stored and backed up, how long data should be retained, how data can be transferred and shared, and how data should be anonymized [@filip_san_2023].
1. Study materials (e.g., recruitment materials)
1. Copies of your instruments (e.g., surveys, interview guides, observation forms)
    - Note that these will need to be created before you can submit to your IRB so make sure to consider timing and start building your instruments early enough to give you time to submit to your IRB before data collection
1. Copy of informed consent/assent forms
    - Same as above, give yourself plenty of time to submit before you start participant recruitment
1. If collecting data from sites (e.g., school districts) or sharing data between sites, supporting documentation from those partners may be required (MOUs, data use/sharing agreements, letters of support, confidentiality agreements)
1. If partnering with other institutions, IRB approval letters from partner institutions may also be required

The review process can take several weeks and it is common for the IRB to request revisions to materials. Make sure to review your timeline and give yourself plenty of time to work through this process before you need to begin recruitment and data collection. 

### Agreements {#collect-agreements}

There are several types of agreements that may be required for your research study for both ethical and legal reasons. Here we will discuss the most common type of agreements, informed consent and assent, as well as other agreements used when working with external partners including memorandum of understanding documents, data use agreements, and non-disclosure agreements. 

#### Consents {#collect-consent}

Informed consent involves obtaining a participant's voluntary agreement to participate in your research study. As described in the Belmont Report [@the_national_commission_for_the_protection_of_human_subjects_of_biomedical_and_behavioral_research_belmont_1979], informed consent should meet the following criteria [@huisman_3_nodate]:

- Describe the study and what is expected of the participant
- Use accessible language to ensure comprehension. Avoid technical jargon and explain terms that may not be easily understood.
- Explain that participation is voluntary
- Review how participant privacy will be maintained

With the revised Common Rule, additional requirements for informed consent were added [@fordham_university_revised_nodate].

- The top of the consent must begin with a concise review of key information that allows participants to make informed decisions
- All information must be presented with sufficient detail to make decisions, not just bulleted lists of facts
- The form must disclose any plans to use participant data for other future research

Figure \@ref(fig:fig10-3) shows common elements that are included in a participant consent form [@bellevue_college_elements_nodate; @the_turing_way_community_turing_2022].

<div class="figure" style="text-align: center">
<img src="img/consent.PNG" alt="Common topics to include in an informed consent information sheet" width="100%" />
<p class="caption">(\#fig:fig10-3)Common topics to include in an informed consent information sheet</p>
</div>

Depending on the type of research study, a participant signature or a check box denoting consent may be required. If so, it can be helpful to put the above information on a cover/information sheet, and then have a separate page for signed consent. Before signing, participants should be required to acknowledge that they

- Have read and understood the information provided
- Have been given the opportunity to ask questions
- Understand that their participation is voluntary
- Understand that they may withdraw from the study at any time

Not all studies require active consent [@university_of_virginia_when_nodate]. Some studies may allow passive consent which may be obtained by providing an information sheet to all participants with the following type of information:

_If you consent to be in this study, no additional action is required; simply move forward with the study._ 
_If you choose to withdraw, you can notify a specified contact._

Your institution's IRB will let you know which type of consent is required for your study and what language is required.

##### Data sharing

With an increase in federal data sharing requirements, it is very important to consider how you want to gain consent for public data sharing. @meyer_practical_2018 provides some general best practices to consider when adding language about public data sharing to a consent form.

- Don’t promise to destroy your data (unless your funder/IRB explicitly requires it)
  - Do incorporate data-retention and sharing plans including letting participants know who will have access to their data
- Don’t promise to not share data
  - Do get consent to retain and share data (consider adding the specific repository you plan to share your data in). 
  - Consider offering tiered levels of consent for participants who may not want all of their data publicly shared but will allow some.
- Don’t promise that research analyses of the collected data will be limited to certain topics
  - Do say that data may be used for future research and share general purposes (e.g., replication, new analyses)
- Do review the ways you plan to de-identify data but be thoughtful when considering risks of re-identification (ex: small sample size for sub-groups)

There are essentially three different ways you can go about obtaining consent for data sharing [@gilmore_practical_2018].

1. Include a line about public data sharing in your consent to participate to research.
    - With this method, a participant who consents is agreeing to both participate in the research study and have their data shared publicly.
2. Have participants consent to data sharing at the same time you provide the research study consent, but provide a separate consent form for the purposes of public data sharing.
3. Have participants consent to data sharing on a separate consent form, at a later time, after research activities are completed. 
    - Obtaining consent this way ensures the participants are fully aware of the data collected from them and can make an informed decision about the future of that data. 

A limitation of using method 1, as discussed by Gilmore, et al. [-@gilmore_practical_2018], is that if a participant is uncomfortable with their data being publicly shared, you will then also lose them as a study participant. So method 2 or 3 may be your best option. If you choose to go with method 2 or 3, it is very important that you not only track your participant study consent status in your tracking database (as discussed in Chapter \@ref(track)), but that you also add a field to track the consent status for data sharing so that you only publicly share data for those that have given you permission to do so.


#### Assents

If your study involves participants under the age of 18, you may also be required to obtain a participant assent form, in addition to a parent/guardian consent form. The guidelines for when assent is needed varies across IRBs, but typically if a child is age 7 or older [@duru_institutional_2023], both assent and parent consent is needed. While including similar information as provided in the consent, these are usually shorter forms that require much more simplistic language depending on the age of the child.

#### Collecting consent and assent

Last, many institutions have started collecting electronic consent rather than paper consents, especially with a rise in remote data collection efforts. There are benefits to this method including reducing the manual labor of collecting paper forms and removing the need to store paper forms or scan them into an electronic form. However, there are still a few things to consider before collecting electronic consent [@lee_considerations_2020; @malow_redcap-based_2021].

- Make sure your IRB approves this method
- Use institution and IRB approved tools to collect consent (e.g., Qualtrics, DocuSign)
- Find out what information is required by your IRB (e.g., signature, typed name, check box, date)
- Consider how those consents will be stored (e.g., download PDFs, download spreadsheet, store in collection tool)

If you are collecting paper consent or assent, there are still some additional things to consider.

- If consents are sent out as packets, say to schools, make sure to have a system in place to track who each form belongs to. When consents start coming back, it's possible that names are illegible, or there are duplicate names across sites. Tracking the origin of each form could look something like this:
  - Collecting class rosters ahead of time and pre-printing names and other identifiers (e.g., teacher, school) on consents before sending packets out (if this is allowed by both your IRB and the school)
  - Asking teachers to print student and teacher name on each form before the consents/assents are handed out
- If consents are collected by in-person data collectors, you will want a similar process
  - Either pre-print names on forms or have data collectors print names and other identifiers (e.g., teacher, school) on forms as they are collected

**Templates and Resources**

|Source|Resource|
|--------|-----------|
|Anja Sautmann| Annontated informed consent checklist ^[https://www.povertyactionlab.org/sites/default/files/research-resources/rr_irb_annotated-informed-consent-checklist_0.pdf]|
|Holly Lane, Wilhemina van Dijk|Example parent consent ^[https://www.ldbase.org/system/files/documents/2021-04/HS-ParentConsent.txt]|
|Jeffrey Shero, et al.| Informed consent and waiver of consent cheat sheet ^[https://osf.io/3czbx]
|Jeffrey Shero, Sara Hart| Informed consent template with a focus on data sharing ^[https://figshare.com/articles/preprint/Informed_Consent_Template/13218773]|
|Melissa Kline Struhl|Lookit consent form template 5^[https://github.com/lookit/research-resources/blob/master/Legal/Lookit%20consent%20form%20template%205.md]|
|University of Virginia| A collection of consent and assent templates ^[https://research.virginia.edu/irb-sbs/consent-templates]|


#### Other agreements 

In education research it is common to collaborate with external partners (e.g., school districts, state agencies, nonprofit organizations) to implement a study and collect data. Those partnerships may involve several different types of agreements. Across different types of agencies and even across similar agency types (e.g., across school districts), the agreements required can vary widely. Let's review a few of the types of agreements that you may encounter.

1. Memorandum of understanding (MOU)
   - This agreement provides a framework for collaboration. While not legally binding, it establishes a commitment to the partnership and outlines the responsibilities and expectations of each partner [@duru_grant_2021; @national_center_for_education_statistics_memoranda_nodate; @rel_west_data_nodate]. This document may also be synonymous with a letter of intent or letter of support.
2. Data use agreement (DUA)
   - A DUA is a contractual agreement that provides the terms and conditions for working with data that are restricted-use (i.e., contain sensitive or identifiable information), often protected under laws such as HIPAA or FERPA. In addition to describing what data will be shared and a time frame for sharing, DUAs may include information such as the purposes for which the data can be used, data security and safeguarding expectations, and data destruction rules [@feeney_using_2021; @fsu_office_of_research_research_nodate; @geraghty_formalize_2021]. DUAs are commonly written for data sharing when partnering with school districts. As an example, a DUA may include the terms for sharing, working with, and storing education records data. However, DUAs can be used to provide guidance for outgoing data as well (i.e., a researcher is sharing their original data with an agency). DUAs can be standalone documents or may be incorporated into an MOU.
3. Non-disclosure agreement (NDA) 
    - NDAs, which also may be synonymous with confidentiality agreements, restrict the use of proprietary or confidential information [@university_of_washington_sharing_nodate] and are legally enforceable agreements.
    
Not only do the types of agreements required differ across partners, but how and when those agreements are submitted will also vary. As one example, when working with school districts, some districts may have informal data request systems in place where you simply submit required documentation for approval. Others may have formal systems in place, including their own institutional review process that involves a committee reviewal timeline. This process is often kicked off by submitting a research request application. In addition to providing information about the study, these requests often ask researchers to submit documents such as:

- The researcher's institutional approved IRB documentation
- Any required agreement forms (e.g., DUA, NDA, confidentiality agreement)
- Consent/assent forms
  - This may be a copy of the consent/assent forms submitted to your institutional IRB. However, in some cases, districts may require an additional consent form to be completed by parents, specifying the specific records that will be shared, before disclosing education records [@university_of_michigan_guidance_2019].

Last, the order of when IRB applications are submitted and when these agreements are made will depend on both the IRBs you working with, as well as your research partners and external collaborators so make sure to start having these discussions early in order to have documents ready in an appropriate timeline.

**Templates and Resources**

|Source|Resource|
|--------|-----------|
|Amy O’Hara| Sample text for data use agreements ^[https://admindatahandbook.mit.edu/book/v1.0-rc4/appendix/dua_appendix.pdf]|
|Columbia Public Schools|CPS Request Research Process^[https://www.cpsk12.org/cms/lib/MO01909752/Centricity/Domain/8329/Research_Process.pdf]|
|Florida State University| Example data use agreement ^[https://www.research.fsu.edu/media/1091/hipaadatause.doc]|
|REL West | Data use agreement checklist ^[https://ies.ed.gov/ncee/rel/regions/west/relwestFiles/pdf/CRP_Data_Sharing_Agreements_and_MOUs.pdf]|
|University of North Carolina|Data use agreement decision making flow chart ^[https://research.unc.edu/wp-content/uploads/sites/61/2013/04/CCM3_039360.pdf]|
|University of Texas at Dallas|Common types of agreements ^[https://research.utdallas.edu/researchers/contracts/types-of-agreements]|


## Quality Assurance {#collect-assurance}

<div class="figure" style="text-align: center">
<img src="img/data_collected7.PNG" alt="Common education research data collection methods" width="100%" />
<p class="caption">(\#fig:fig10-4)Common education research data collection methods</p>
</div>

Now that we have a baseline understanding of ethical and legal considerations, we can dive in to protecting data quality during data collection. Education researchers collect original data in many ways (see Figure \@ref(fig:fig10-4)). The focus of this chapter will be on data collected via forms (i.e., a document with spaces to respond to questions). Forms are widely used to collect data in education research (think surveys, assessments, observation forms, or a progress monitoring form on a website), yet if developed poorly, they can produce some of the most problematic data issues. On the flip side, if the practices discussed in this chapter are implemented, forms can also be the easiest tool to remedy issues with. 

The focus on forms is not to discount the importance of data collected through other means such as video or audio recording, where issues such as participant privacy and data security and integrity should absolutely also be considered. However, even with those types of data collection efforts, often teams are ultimately still coding that data using some sort of form (e.g., observation form), further supporting the need to build forms that collect quality data.

When collecting information using forms you can certainly do your best to fix data errors after data collection during a cleaning process. However, one of the most effective ways to ensure quality data is to correct it at the source. This means designing items and building data collection tools in a way that produces valid, reliable, and more secure data. When creating your original data collection instruments, there are four ways to collect higher quality data.

1. Using good questionnaire design principles
2. Implementing a series of pilot test
3. Choosing data collection tools that meet your needs
4. Building your instrument with the end in mind

We will discuss each of these phases below. 

> **Note** <br> <br>
If you are collecting data using a standardized assessment, along with a provided instrument (e.g., a computer-adaptive testing program), most of the information in this section will not be applicable. In those situations, it is best to adhere to all guidelines provided by the assessment company.

### Questionnaire design {#collect-design}

In Chapter \@ref(document) we discussed the importance of documenting all instrument items in your data dictionary before creating your data collection instruments. As you develop items to add to your data dictionary, it is vital to consider questionnaire design.

While some instruments (e.g., cognitive assessments) typically have standardized items, other instruments, such as surveys, are often not predefined, allowing researchers freedom in the design of the instrument which can lead to negative effects such as errors, bias, and potential harm [@dime_analytics_data_2021; @northern_illinois_university_data_nodate]. Question ordering, response option ordering, question wording, and more can all impact participant responses. While questionnaire design is actually outside of the scope of this book, I have a few tips to help you collect more valid, reliable, and ethical survey data. In addition to following these tips, make sure to consult a methodologist when designing your questionnaire.

1. Use existing standards if possible
    - Organizations such as the @national_institutes_of_health_common_nodate and the @national_center_for_education_statistics_common_nodate have developed repositories (Common Data Elements^[https://www.nlm.nih.gov/oet/ed/cde/tutorial/03-100.html] and Common Education Data Standards^[https://ceds.ed.gov/]) of standardized question wording paired with a set of allowable response options for commonly used data elements. Using standards when collecting commonly used variables, such as demographics, provides the following benefits [@icpsr_introduction_2022; @kush_fair_2020]:
        - Reduces bias
        - Allows for harmonization of data across your own research studies and also across the field
            - This allows researchers to draw conclusions using larger samples or by comparing data over time
            - It also reduces the costs of integrating datasets
        - Improves interpretation of information
2. Make sure questions are clearly worded and answer choices are clear and comprehensive
	- Consider how the language might be interpreted. Is the question wording confusing? Can the response options be misinterpreted?
	    - Rather than asking "What county are you from?" when looking for the participant's current location, be more specific and ask "What county do you currently reside in?"
	    - Rather than asking "Which parent are you?" and providing the response options "m" and "f", where "m" and "f" could be interpreted as "male" or "female", clearly write out the response options and make sure they are comprehensive (mother, father, legal guardian, and so forth)
	    - Rather than asking "Do your children not have siblings?" which can be confusing, remove the negative and ask "Do your children have siblings?" [@reynolds_basics_2022]
	  - Is the question leading/biased?
	    - Are the response options ordered in a leading way?
	  - Is there no one way to answer this question?
	    - Are response categories mutually exclusive and exhaustive [@icpsr_guide_nodate]?
3. Consider data ethics in your questionnaire design [@gaddy_principles_2020; @kaplowitz_5_2020; @kopper_survey_2021; @mathematica_tips_nodate; @narvaiz_data_nodate]
    - Consider the why of each item and tie your questions to outcomes
        - Don't cause undue burden on participants by collecting more data just to have more data
        - If collecting demographic information, provide an explanation of why that information is necessary and how it will be used in your research
    - Review question wording
      - Does it have potential to do harm to participants? Do the benefits outweigh the risks?
      - If sensitive questions are included, make sure to discuss how you will protect respondent's information
    -  Make questions inclusive of the population while also capturing the categories relevant for research
        - If a question is multiple choice, still include an "other" option with an open-text field
        - For demographic information, allow participants to select more than one option
	  - Consider including one general free-text field in your survey to allow participants to provide additional information that they feel was not captured elsewhere
4. Limit the collection of personally identifiable information (PII)
    - Collecting identifiable information is a balancing act between protecting participant confidentiality and collecting the information necessary to implement a study. We often need to collect some identifying information either for the purposes of record linking or for purposes related to study outcomes (e.g., scoring an assessment based on participant's age). 
    - As a general rule, you only want to collect PII that is absolutely necessary for your project, and no more [@gaddy_principles_2020]. As discussed in Chapter \@ref(rdm), PII can include both direct identifiers (e.g., name or email) as well as indirect identifiers (e.g., birthdate). Before sharing your data, all PII will need to be removed or altered to protect confidentiality.

**Survey Design Resources**

|Source|Resource|
|--------|-----------|
|Sarah Kopper, Katie Parry|Survey design ^[https://www.povertyactionlab.org/resource/survey-design]|
|Pew Research Center|Writing survey questions ^[https://www.pewresearch.org/our-methods/u-s-surveys/writing-survey-questions/]|
|Stefanie Stantcheva| How to run surveys: A guide to creating your own identifying variation and revealing the invisible ^[https://www.nber.org/system/files/working_papers/w30527/w30527.pdf]|
|World Bank|Survey content-focused pilot checklist ^[https://dimewiki.worldbank.org/Checklist:_Content-focused_Pilot]|

### Pilot the instrument

Gathering feedback on your instruments is an integral part to the quality assurance process. There are three phases to piloting an instrument [@dime_analytics_survey_2021] (see Figure \@ref(fig:fig10-5)):

1. Gathering internal feedback on items
    - As discussed in Chapter \@ref(document), once all items for each instrument have been added to your data dictionary, have your team review the data dictionary and provide feedback
2. Piloting an instrument for content
    - Once the team has approved the items to be collected, the second phase of piloting can begin. Create a printable draft of your instrument that can be shared with people in your study population and gather feedback
    - If you are piloting your instrument with a small population (N < 10), and you are either gathering feedback from a checklist or collecting data using the instrument with no intent to disseminate outcomes as research data, then IRB approval will most likely not be required [@cornell_university_irb_2019; @stanford_university_use_nodate]. With that said, you should always consult with your institution's IRB because rules can vary.
3. Piloting the instrument for data related issues
    - Once the instrument is created in your chosen data collection tool, share the instrument with your team for review
    - Here we are most interested in whether or not the data we are collecting are accurate, comprehensive, and usable
    - We will discuss this phase in greater detail in Section \@ref(collect-build)

Last, as you move through the piloting phases, remember to update any changes not only in your tool but also in your data dictionary and any other relevant documentation.
	  
<div class="figure" style="text-align: center">
<img src="img/pilot2.PNG" alt="Data collection instrument pilot phases" width="100%" />
<p class="caption">(\#fig:fig10-5)Data collection instrument pilot phases</p>
</div>


### Choose quality data collection tools {#collect-tools}

Once content piloting is completed, teams should be ready to begin building their instruments in their data collection tools (see Figure \@ref(fig:fig10-4)). Research teams may be restricted in the tools they use to collect their data for a variety of reasons including limited resources, research design, the population being studied, or the chosen instrument (e.g., an existing assessment can only be collected using a provided tool). However, if you have the flexibility to choose how you collect your data, pick a tool that meets the various needs of your project while also providing data quality and security controls. Things to consider when choosing a data collection tool are:

1. Pick the tool that meets the needs of your project
    - Is crowdsourcing required? 
    - Is multi-site access required?
    - Who is entering the data (i.e., data collectors, participants)?
      - If participants are entering data, is the tool accessible for your population?
    - What are the technical requirements for the tool (i.e., will internet be available if you plan to use a web-based tool)?
    - Does the tool have customizable features that are necessary for your instrument (e.g., branching logic, automated email reminders, options to embed data, options to calculate scores in the tool)?
1. Compliance and security
    - If you collect identifiable data, is the tool HIPAA compliant? FERPA compliant? (see Chapter \@ref(rdm) for more information about these regulations)
    - Is the tool approved by your institution?
    - If collecting anonymous data, do you have the option to anonymize responses in the tool (e.g., remove IP Address and other identifying metadata collected by the tool)?
1. Training needed
    - Is any additional team training needed to allow your team to use and/or build instruments in the tool?
1. Associated costs
    - Is there a cost associated with the tool? Do you have the budget for the tool?
    - Will there be additional costs down the line (e.g., collecting data on paper means someone will need to hand enter the data later)?
1. Data quality features
    - Does the tool allow you to set up data validation?
    - Does the tool have version control?
    - Does the tool have features to deal with fraud/bots?

While there are a variety of tool options, in a nutshell when it comes to data collected via forms, we are collecting data in one of two ways---electronic or paper. In addition to choosing tools based on the above criteria, there are some general benefits associated with each method that should also be considered [@cohen_research_2007; @douglas_data_2023; @gibson_data_2021; @icpsr_guide_nodate;  @malow_redcap-based_2021; @society_of_critical_care_medicine_building_2018; @van_bochove_data_nodate].

<div class="figure" style="text-align: center">
<img src="img/collect_benefits2.PNG" alt="Comparison of data collection tool benefits" width="100%" />
<p class="caption">(\#fig:fig10-6)Comparison of data collection tool benefits</p>
</div>

> **Note** <br> <br>
If you choose to collect data in an electronic format, I highly recommend using a web-based tool that directly feeds into a shared database rather than through offline tools that store data on individual devices. Using a web-based tool, all data is stored remotely in the same database and can be easily downloaded or connected to at any time. No additional work is required. <br> <br>
However, when collecting data on various tablets in the field, if the forms are offline and cannot be later connected to a web-based form, then all data will be stored individually on each tablet. This not only may be less secure (e.g., a tablet becomes corrupted), it may also require additional data wrangling work including downloading data from each tablet to a secure storage location each day and then combining all files into a single dataset. If you use an electronic tool but your site does not have internet, consider using one of the many tools (e.g., Qualtrics, SurveyCTO) that allow you to collect data using their offline app and then upload that data back to the platform once you have an internet connection again.

**Tool Comparison Resources**

|Source|Resource|
|--------|-----------|
|Michael Gibson, Wim Louw|Survey platform comparison^[https://www.povertyactionlab.org/resource/survey-programming]|
|Washington State University Libraries|Software for sensitive data^[https://libguides.libraries.wsu.edu/rdmlibguide/ethics]|
|Benjamin Douglas, et al. | Data quality in online human-subjects research comparison of tools^[https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0279720]|


### Build with the end in mind {#collect-build}

Last, you want to build your tool with the end in mind. This means taking time to consider how the data you collect will be translated into a dataset [@beals_data_2014; @lewis_how_2022; @uk_data_service_quality_2023]. Recall from Chapter \@ref(structure), we ultimately need our data to be in a rectangular format, organized according to the basic data organization rules, in order to be analyzable. 

The process for building your tools with the end in mind is fairly different for electronic tools compared to paper forms so we are going to talk about these two processes separately.

#### Electronic data collection {#collect-electronic}

The first thing you will want to do before building your tool is bring out your data dictionary. This data dictionary will be your guide as you build your instrument. Some tools, such as REDCap, provide the option to upload your data dictionary which can then be used to automate the creation of data collection forms as opposed to building them from scratch [@patridge_research_2018].

However, if you are building your instrument manually, adhering to the following guidelines will ensure you collect data that is easier to interpret and more usable, and it will also reduce the amount of time you will need to spend on future data cleaning [@lewis_how_2022].

1. Include all items from your data dictionary
    - This includes all substantive questions, as well as items that are necessary for linking purposes (e.g., participant identifiers, rater ids for inter-rater reliability)
    - This does not include any variables from your data dictionary that will be derived (e.g., sum scores) or any grouping variables that will be added in during the data cleaning phase (e.g., treatment, cohort)
1. Name all of your items the correct variable name from your data dictionary [@uk_data_service_quality_2023]
    - For example, instead of using the platform default name of "Q2", rename the item to "tch_years"
    - As we mentioned in Chapter \@ref(style), it's also best to not concatenate a time component to your variable names if your project is longitudinal. Doing so makes it difficult to reuse your instrument for other time periods, creating additional work for you or your team.
1. Code all values as they are in your data dictionary
    - For example, 1 = "strongly agree", 2 = "agree", 3 = "disagree", 4 = "strongly disagree"
    - Many times tools assign a default value to your response options and these values may not align with what you've designated in your data dictionary
    - As you edit your survey, continue to check that your coded values did not change due to reordering, removal, or addition of new response options
1. Use data validation to reduce errors and missing data [@uk_data_service_quality_2023]
    - Content validation for open-text boxes
      - Restrict entry to the type assigned in your data dictionary (e.g., numeric)
      - Restrict entry to the format assigned in your data dictionary (e.g., YYYY-MM-DD)
      - Restrict ranges based on allowable ranges in your data dictionary (e.g., 1-50)
          - This could even include validating against previous responses (e.g., if SchoolA was selected in a previous question, grade level should be between 6-8, if SchoolB was selected, grade level should be between 7-8)
    - Response validation
      - Consider the use of forced-response and request-response options to reduce missing data
        - Forced-response options do not allow participants to move forward without completing an item. Request-response options notify a respondent if they skip a question and ask if they still would like to move forward without responding
        -  Be aware that adding a forced-response option to sensitive questions has the potential to be harmful and produce bad data. If adding a forced-response option to a sensitive question, consider allowing those participants to opt-out in another way (e.g., "Prefer not to answer"). 
1. Choose an appropriate type and format to display the item
    - Become familiar with the various questions types available in your tool (e.g., rank order, multiple choice, text box, slider scale)
    - Become familiar with the various formats (e.g., radio button, drop-down, checkbox)
    - For example, if your item is a rank order question (ranking 3 items), creating this question as a multi-line, free-text entry form may lead to duplicate entries (such as entering a rank of 1 more than once). However, using something like a rank order question type with a drag and drop format ensures that participants are not allowed to duplicate rankings.
1. If there is a finite number of response options for an item, and the number isn’t too large (less than ~ 20) use controlled vocabularies (i.e., a pre-defined list of values) rather than an open-text field [@openaire_eu_basics_2018; @uk_data_service_quality_2023]
    - For example, list school name as a drop-down item rather than having participants enter a school name
      - This prevents variation in text entry (e.g., "Sunvalley Middle", "sunvalley", "Snvally Middle"), which ultimately creates unnecessary data cleaning work and may even lead to unusable values
1. If there is an infinite number of response options for an item or the number of options is large, use an open-text box
    - If you can create a searchable field in your tool, allowing your participants to easily sift through all of the options, you absolutely should. Otherwise, use a text-box as opposed to having participants scroll through a large list of options
    - Consider adding examples of possible response options to clarify what you are looking for
    - Using open-ended text boxes does not mean you cannot regroup this information into categories later during a cleaning process. It is just more time-consuming and requires interpretation and decision-making on the part of the data cleaner
1. Only ask for one piece of information per question 
    - For example, rather than asking "Please list the number of students in your algebra class and geometry class", split those into two separate questions so those questions download as two separate items in your dataset
    - This also includes more simple examples such as splitting first name and last name into two separate fields
    - This prevents confusion in case a participant or data collector swaps the order of information
1. To protect participant privacy and ensure the integrity of data, consider adding a line to the introduction of your web-based instrument, instructing participants to close their browser upon completion so that others may not access their responses
1. Last, if possible, export the instrument to a human-readable document to perform final checks
    - Are all questions accounted for?
    - Are all response options accounted for and coded as they should be?
    - Is skip logic shown as expected?

Once your tool is created, the last step is to pilot for data issues (see Figure \@ref(fig:fig10-5)). Collect sample responses from team members. Create a feedback checklist for them to complete as they review the instrument [@gibson_survey_2020]. Assign different reviewers to enter the survey using varying criteria (e.g., different schools, different grade levels). Let team members know that they should actively try to break things [@kopper_questionnaire_2020]. Try to enter nonsensical values, try to skip items, try to enter duplicate entries. If there are problems with the tool, now is the time to find out. 

After sample responses are collected from team members, export the sample data using your chosen data capture process (see Chapter \@ref(capture)) and review the data for the following:

1. Are there any unexpected or missing variables?
2. Are there any unexpected variable names?
3. Are there unexpected values for variables?
4. Are there missing values where you expect data?
5. Are there unexpected variable formats?
6. Is data exporting in an analyzable, rectangular format?

If any issues are found either through team feedback or while reviewing the exported sample data, take time to update the tool as well as your documentation as needed before starting data collection.

Last, this is also the time to update your data dictionary. As you review your exported file, update your data dictionary to reflect any unexpected variables that are included (e.g., metadata), any unexpected formatting, as well as any newly discovered recoding or calculations that will be required during the data cleaning process. As an example, if upon downloading your sample data you learn that a "select all" question differently than you expected, now is the time to add this information, along with any necessary future transformations, to your data dictionary.

#### Paper data collection {#collect-paper}

There are many situations where collecting data electronically may not be feasible or the best option for your project. While it is definitely trickier to design a paper tool in a way that prevents bad data, there are still steps you can take to improve data quality.

1. Use your data dictionary as a guide as you create your paper form
    - Make sure all questions are included and all response options are accurately added to the form
2. Have clear instructions for how to complete the paper form [@kopper_survey_2021]
   - Make sure to not only have overall instructions at the top of the form but also have explicit instructions for how each question should be completed
      - Where to write answers (e.g., not in the margin)
      - How answers should be recorded (e.g., YYYY-MM-DD, or 3 digit number)
      - How many answers should be recorded (e.g., circle only one answer, check all applicable boxes)
      - How to navigate branching logic (e.g., include visual arrows)
3. Only ask for one piece of information per question to reduce confusion in interpretation

Once your tool is created, you will want to pilot the instrument with your team for data issues (see Figure \@ref(fig:fig10-5)). Using the feedback collected, edit your tool as needed before sending it out into the field.

Last, unless paper data it is collected using a machine-readable form, it will need to be manually entered into an electronic format during the data capture phase. While we will talk about data entry specifically in Chapter \@ref(capture), this point in instrument creation is a great time to create an annotated instrument [@neild_sharing_2022]. This includes taking a copy of your instrument and writing the associated codes alongside each item (i.e., variable name, value codes). This annotated instrument can be useful during the data entry process and serve as a linking key between your instrument and your data dictionary (see Figure \@ref(fig:fig10-7)) [@hart_florida_2018].

<div class="figure" style="text-align: center">
<img src="img/annotated_instrument.PNG" alt="Annotated instrument from The Florida State Twin Registry project" width="80%" />
<p class="caption">(\#fig:fig10-7)Annotated instrument from The Florida State Twin Registry project</p>
</div>

#### Identifiers

When building data collection tools, no matter if they are paper or electronic, it is vitally important to make sure you are collecting unique identifiers [@kopper_survey_2021]. Whether you have participants enter a unique identifier into a form or you link study ID to each form in some other way, it's important to not accidentally collect anonymous data. Without unique identifiers in your data, you will be unable to link data across time and forms. If possible, you want to avoid collecting names as unique identifiers for the following reasons [@mckenzie_falsehoods_2010]:

- To protect confidentiality we want to use names as little as possible on forms
  - If they are used on forms, we want to remove them as soon as possible
- Names are not unique
  - If you do collect names, you'll want to ask for additional identifying information that when combined, make a participant unique (e.g., student name and email)
- Names change (e.g., someone gets married/divorced)
- There is too much room for error
  - If names are hand entered, there are endless issues with case sensitivity, spelling errors, special characters, spacing, and so forth

All of the above issues make it very difficult to link data. If you do decide to collect names, remember that you will need to remove names during data processing and replace them with your unique study identifiers.

Figure \@ref(fig:fig10-8) shows what a data de-identification process looks like [@otoole_data_2018]. Dataset 1 would be the incoming survey data with identifiers, Dataset 2 would be a roster exported from your participant database (see Chapter \@ref(track)), and Dataset 3 is your clean, de-identified dataset, created by merging Dataset 1 with Dataset 2 on your unique identifier and dropping your identifying variables. I want to emphasize the importance of using a "merge" which we will discuss more in Chapter \@ref(clean), as opposed to replacing names with IDs by hand entering identifiers. If at all possible, we want to completely avoid hand entry of study IDs. Hand entry is error-prone and can lead to many mistakes.

<div class="figure" style="text-align: center">
<img src="img/de-identify.PNG" alt="Process of creating a de-identified dataset" width="90%" />
<p class="caption">(\#fig:fig10-8)Process of creating a de-identified dataset</p>
</div>

Rather than having to de-identify your data through this cleaning process, another option is to collect a different type of unique identifier, or pre-link unique study identifiers and names in your instrument, removing many of the issues above [@dime_analytics_data_2021; @gibson_survey_2020]. We will discuss these methods separately for electronic data and paper data.

> **Note** <br> <br>
If your study is designed to collect anonymous data, then you will not assign study identifiers and no participant identifying information should be collected in your instruments (e.g., name, email, date of birth). You will also want to make sure that if your tool collects identifying metadata such as IP Address or worker IDs in the case of crowdsourcing tools (e.g., MTurk), this information will not be included in your downloaded data. <br><br>
Remember that if you collect anonymous data, you will not be able to link data across measures or across time. However, if your study randomizes participants by an entity (e.g., school or district), you will need to collect identifying information from that entity in order to cluster on that information (e.g., school name).

##### Electronic Data

There are many ways you might consider collecting unique identifiers other than names. A few possible options are provided below. The method you choose will depend on your data collection design, your participant population, your tool capabilities, and your team expertise.

1. Create unique links for participants
    - Many tools will allow you to preload a contact list of participants (from your participant database) that includes both their names and study IDs. Using this list, the tool can create unique links for each participant. This is the most error-proof way to ensure study IDs are entered correctly. 
    - When you export your data, the correct ID is already linked to each participant and you can choose to not export names in the data. 
    - If using this method, make sure to build a data check into the system. When a participant opens their unique link, verify their identity by asking, “Are you {first name}?” or "Are your initials {initials}?". In order to protect other participant identities, do not share full names. 
      - If they say yes, they move forward. If they say no, the system redirects them to someone to contact. This ensures that participants are not completing someone else’s survey and IDs are connected to the correct participant.
2. Provide one link to all participants and separately, in an email, in person, or by mail, provide participants with their study ID to enter into the system. 
    - This might be a preferred method if you are collecting data in a computer lab or on tablets at a school site, or if your tool does not have the option to create unique links
    - This can possibly introduce error if a participant enters their study ID incorrectly. 
      - Similar to the first option, after a participant enters their ID, verify their identity
    - Note that participants are only becoming aware of their own study identifier, not the identifiers associated with other participants. However, if your team, or your IRB, is uncomfortable with participants knowing their study IDs you can also consider using a "double ID" which is yet another set of unchanging unique identifiers that you use for the sole purpose of data collection. Those identifiers will need to be tracked in your participant tracking database and will need to be replaced with study IDs in the clean data
3. If you have not previously assigned study identifiers (i.e., your consent and assent process is a part of your instrument), you can have participants enter their identifying information (e.g., name) and then have the tool assign a unique identifier to the participants
    - Using this method, you can potentially download two separate files
      - One with just the instrument data and assigned study ID, with name removed
      - One with just identifying information and assigned study ID (this information will be added to your participant tracking database)
    
##### Paper Data

If you take paper forms into the field consider doing the following to connect your data to a participant [@otoole_data_2018; @reynolds_basics_2022].

- Write the study ID, and any other relevant identifiers (e.g., school ID and teacher ID), on each page of your data collection form and then use either a removable label with participant name and other relevant information and place that over the ID or attach a cover sheet with this information. When you return to the office, you can remove the name label/cover sheet and be left with only the ID on the form.
  - It is this ID only that you will enter into your data entry form during the data capture process, no name.
  - Removing the label/cover sheet also ensures that your data entry team only sees the study ID when they enter data, increasing privacy by minimizing the number of people who see see participant names.
  - It is important to double and triple check study identifiers against your participant database to make sure the information is correct before removing the label or cover sheet
  - Make a plan for the labels/cover sheets (either shred them if they are no longer needed, or store them securely in a locked file cabinet and shred them at a later point)

<div class="figure" style="text-align: center">
<img src="img/cover_sheet2.PNG" alt="Example cover sheet for a paper data collection instrument" width="90%" />
<p class="caption">(\#fig:fig10-9)Example cover sheet for a paper data collection instrument</p>
</div>

## Quality Control

In addition to implementing quality assurance measures during your planning phases, it is equally important to implement several quality control measures while data collection is underway. Those measures include:

1. Field data management
2. Ongoing data checks
3. Tracking data collection daily
4. Collecting data consistently

We will discuss each of these measures now.

### Field data management

If your data collection efforts include field data collection (e.g., data collectors administering assessments in a school), there are several steps your team can implement that will keep your data more secure in the field, help a project coordinator keep better track of what happens in the field, and will lead to more accurate and usable data. Some best practices for field data collection include the following [@dime_analytics_data_2021]:

- Keep your data secure in the field
  - Make sure all paper forms are kept in a folder (or even a lock box) with you at all times and that they are promptly returned to the office (e.g., not left in a car, not left at someone's home)
  - Make sure all data collection devices (e.g., phones, tablets) are password protected and never left open and unattended. Keep all identifiable information encrypted on your field devices (i.e., data is encoded so that only those with a password can decipher it). You may also consider remote wiping capabilities on portable devices in the case of loss or theft [@otoole_data_2018]
- Create tracking sheets to use in the field
  - These sheets should include the names and/or identifiers of every participant who data collectors will be collecting data from
  - Next to each participant, include any other relevant information to track such as 
    - Was the data collected (i.e., a check box)
    - Who collected the data (i.e., data collector initials or ID)
    - Date the data was collected
    - As well as a notes section to describe any potential issues with the data (e.g., "Student had to leave the classroom halfway through the assessment - only partially completed")
  - This tracking sheet allows the project coordinator to keep track of what is occurring in the field so that information can be accurately recorded in the participant tracking database and forms can be sent back out for completion as needed
- Check paper data in the field
  - Immediately upon completing a form, have data collectors do spot checks. If any problems are found, follow up with the participant for correction if possible.
    - Check for missing data
    - Check for duplicate answers given
    - Check for answers provided outside of the assigned area (e.g., answers written in the margins)
    - Check calculations and scoring (e.g., basals, ceilings, raw scores)
- Assign a field supervisor. This person is assigned to:
  - Do another round of data checks in the field once the data collector returns paper forms to the on-site central location (e.g., if data collectors have set up in the teacher's lounge)
  - Ensure that all data and equipment is accounted for and returned to the office
  - Be available for trouble shooting as needed
- Do another round of paper data spot checking as soon as the data is returned to the office (see Figure \@ref(fig:fig10-10))
  - The project coordinator may do this round of checking as they are tracking information in the participant database
  - If any issues are found, note that in the tracking database and send the form back out to the field for correction
  - If your paper forms are mailed back to you from participants, rather than returned from field data collectors, it is still important to do in-office spot checks. If at all possible, reach out to those participants for any corrections.
- When a wave of data collection wraps up, collect feedback from data collectors to improve future data collection efforts
  - What went well? What didn't?

<div class="figure" style="text-align: center">
<img src="img/spot_check.PNG" alt="A series of spot checks that occur with paper data" width="100%" />
<p class="caption">(\#fig:fig10-10)A series of spot checks that occur with paper data</p>
</div>

**Tracking sheet templates**

|Source|Resource|
|--------|-----------|
|Crystal Lewis| Field tracking sheet template ^[https://docs.google.com/spreadsheets/d/1CeIXvTBtU9O3GNzfFaAMtb69Z2HyOLuPQWsxy7jOWdU/edit?usp=sharing]|

### Ongoing data checks

If you collect data via a web-based form, you will want to perform frequent data quality checks, similar to the checks you performed during the content and data piloting phase. You will want to check for both programming errors (i.e., skip logic programmed incorrectly) as well as response quality errors (e.g. bots, survey comprehension) [@dime_analytics_data_2021; @gibson_data_2021].

- Checks for comprehension
  - Are any questions being misinterpreted?
- Checks for missing data
  - Are items being skipped that should not be skipped?
  - Are participants/data collectors not finishing forms?
- Checks for ranges and formats
  - Are values in unexpected formats or falling outside of unexpected ranges?
- Checks for duplicate forms
  - Are there duplicate entries for participants?
- Is skip logic working as expected?
  - Are people being directed to the correct location based on their responses to items?

Some of these checks can be performed programmatically (i.e., you can write a validation script in a program such as R, and run that script on a recurring schedule during data collection to check for things such as values out of range). Other checks may be a manual check of data (e.g., such as downloading your data on a recurring schedule and reviewing open-ended questions for nonsensical responses). If errors are found, consider revising your instrument to prevent future errors if this is possible without jeopardizing the consistency of your data.

> **Note** <br> <br>
All of the web-based data collection efforts in this chapter assume you are making a private link that you are sharing with a targeted list (e.g., students in a classroom, teachers in a school). However, there may be times when you need to publicly recruit and collect data for your study and this opens your instrument up for a plethora of data quality issues. Bots, fraudulent data, and incoherent or synthetic responses are all issues that can plague your online data collection efforts, particularly with crowdsourcing platforms [@douglas_data_2023; @veselovsky_artificial_2023; @webb_too_2022]. If possible, avoid using public survey links. One possible workaround would be to first create a public link with a screener. Then after participants are verified through the screener, send a private, unique link to the instrument. <br><br>
If a workaround is not possible and you need to use a public link, some suggestions that can help you both secure your instrument and detect fraud include the following [@arndt_collecting_2022; @simone_how_2019; @teitcher_detecting_2015]:   
- Not posting the link on social media  
- Using CAPTCHA verification  
- Using tools that allow you to block suspicious geolocations  
- Not automating payment upon survey completion    
- Including open-ended questions   
- Building attention/logic checks into the survey  
- Asking some of the same questions twice (once early on and again at the end)   <br><br>
Last, check your data thoroughly for bots or fraudulent responses before analyzing it and before providing payments to participants. The following types of things are worth looking into further:  
- Forms being completed in a very short period of time   
- Forms being collected from suspicious geolocations    
- Duplicated or nonsensical responses to open-ended questions  
- Nonsensical responses to attention or logic checking questions    
- Inconsistent responses across repeated questions  

### Tracking data collection

Throughout data collection your team should be tracking the completion of forms (e.g., consents, paperwork, data collection forms). Your team may designate one person to track data (e.g., the project coordinator), or they may designate multiple. If you are working across multiple sites, with multiple teams, you will most likely have one or more people at each site tracking data as it comes in. 

Some tracking best practices include:

1. Only track data that you physically have (paper or electronic)
    - Never track data as "complete" that someone just tells you they collected. 
      - You can always mark this information in a "notes" field but do not track it as "complete" until you have the physical data. 
2. Track daily during data collection
    - Do not wait until the end of data collection to track what data was collected
    - This helps ensure that you don't miss the opportunity to collect data that you *thought* you had but never actually collected
3. Only track complete data as "complete"
    - Review all data before marking it as complete, including consents, assents, and other administrative forms. If a form is only partially completed and you plan to send it back out to the field for completion, mark this in the "notes" but do not mark it as "completed". If you have a "partially completed" option, you can mark this option.

### Collecting data consistently

As mentioned in Chapter \@ref(style), it's important to collect data consistently for the entire project to ensure interoperability. Keep the following consistent across both time and forms (e.g., Spanish and English version of a form, link for SchoolA and link for SchoolB):

- Variable names
  - Use the same names for the same items (and remember it's best to not add a time component to your variable names at this time)
- Variable types
  - For example, if gender is collected as a numeric variable, keep it as a numeric variable
- Value codes
  - Make sure response options are consistently coded using the same values (e.g., 0 = "No", 1 = "Yes")
- Question type and format
  - If a slider question was used for "Percent of time on homework", continue to ask that question using a slider question
  
Failing to collect your data consistently has many consequences:

1. It can make it difficult or impossible to compare outcomes
2. It makes your work less reproducible
3. It reduces your ability to physically combine data (i.e., you cannot append dissimilar variables)
4. It can lead to errors in interpretation

Last, collecting data consistently also means measuring things in the same way over time or across forms so that you don't bias your results. The slightest change in item wording or response options can result in dramatic changes to outcomes [@icpsr_introduction_2022; @pew_research_center_writing_2023].

## Review

Recall from Chapter \@ref(plan), we discussed designing and visualizing a data collection workflow during your planning phase. As we've learned from this chapter, errors can happen at any point in the workflow so it is important to consider the entire data collection process holistically and integrate both quality assurance and quality control procedures throughout. Figure \@ref(fig:fig10-11) helps us to see when these practices fit into the different phases our workflow.

Once your workflow is developed and quality assurance and control practices are integrated, consider how you will ensure that your team implements these practices with fidelity. Document the specifics of your plan in an SOP (see Chapter \@ref(document)), including assigning roles and responsibilities for each task in the process. Last, train your team on how to implement the data collection SOP, and implement refresher trainings as needed. 

<div class="figure" style="text-align: center">
<img src="img/data_collect_workflow2.PNG" alt="Integrating quality assurance and control into a data collection workflow" width="100%" />
<p class="caption">(\#fig:fig10-11)Integrating quality assurance and control into a data collection workflow</p>
</div>

**Instrument Workflow Resources**

|Source|Resource|
|--------|-----------|
|DIME Wiki| Questionnaire design timeline^[https://dimewiki.worldbank.org/Questionnaire_Design]|
|Sarah Kopper, Katie Parry | Five key steps in the process of survey design^[https://www.povertyactionlab.org/resource/survey-design]|

