---


---

<hr>
<h2 id="title-release-noteskeywords-development-versioningtags-developmentsidebar-overview_sidebarpermalink-overview_release_notes.htmlsummary-summary-release-notes-of-the-versions-released-in-the-uec-digital-integration-programme-implementation-guide">title: Release Notes<br>
keywords: development, versioning<br>
tags: [development]<br>
sidebar: overview_sidebar<br>
permalink: overview_release_notes.html<br>
summary: Summary release notes of the versions released in the UEC Digital Integration Programme Implementation Guide</h2>
<h2 id="release-candidate-proposed.">2.0-Release Candidate (proposed).</h2>
<p>The next version of the CDS API Implemenation Guide will introduce additional guidance and introduce the UEC Encounter Report. It is proposed as a Release Candidate to be published in spring 2020.</p>
<h2 id="alpha">1.1.0-alpha</h2>
<ul>
<li><code>ProcedureRequest</code> Resource has been deprecated</li>
<li>Added guidance to state that all Assertions are to be <code>Observation</code> resources</li>
<li>Removed guidance pages regarding <code>Encounter</code> and <code>Patient</code> resources as they now follow CareConnect guidance</li>
<li>Further guidance and updates added on searching for a <code>ServiceDefinition</code> using additional customised <code>SearchParameters</code></li>
<li>Added guidance on usage to the GuidanceResponse page</li>
<li>Updated HTTP 500 error with a more descriptive error message</li>
<li>GuidanceResponse page updated to show occurrenceDateTime represents date/time at which a <code>GuidanceResponse</code> is returned to an EMS</li>
<li>Updated valueset text and links on <code>ReferralRequest</code> page</li>
<li>Corrected name of <code>ServiceDefinition.effective</code> parameter in API general guidance</li>
<li>Updated API general guidance to align errors more closely to an <code>OperationOutcome</code></li>
<li>Further guidance and updates added on searching for a <code>ServiceDefinition</code> using additional customised SearchParameters</li>
<li>Guidance amended regarding the <code>ReferralRequest.intent</code> element</li>
<li>SearchParameters resource page added with examples of <code>SearchParameter</code> definitions</li>
<li><code>RequestGroup</code> resouce page added</li>
</ul>
<h2 id="alpha-1">1.0.0-alpha</h2>
<ul>
<li>Updated COULD to MAY in guidance</li>
<li>Removed GDS Stage - Experimental section from Guide versioning page</li>
</ul>
<h2 id="experimental">0.10.0-experimental</h2>
<ul>
<li>Updated Select <code>ServiceDefinition</code> page to show greater detail on how an EMS would select a <code>ServiceDefinition</code> from a CDSS</li>
<li>Made inclusion of reference to patient mandatory in the <code>ServiceDefinition.$evaluate</code> operation so a CDSS can create a <code>CarePlan</code> and <code>ReferralRequest</code> without error</li>
<li>Added implementation guidance on <code>Encounter</code> and <code>Observation</code></li>
<li>Removed paragraph on Third party care from <code>CarePlan</code> implementation guidance page</li>
<li>Improved formatting and consistency of terms used throughout the Implementation Guide</li>
</ul>
<h2 id="experimental-1">0.9.0-experimental</h2>
<ul>
<li>Added glossary with specific Urgent and Emergency Care and Clinical Decision Support terms</li>
<li>Removed HTTP responses page</li>
<li>Added Communication channels specific to Urgent and Emergency Care and Interoperability Standards</li>
<li>Removed FAQs responses page</li>
<li>Updated Introduction to reference initiatives set out by the Urgent and Emergency Care Digital Integration Programme</li>
<li>Updated Introduction in scope and out of scope sections</li>
<li>Updated Introduction page with Note to Implementers to welcome feedback on the Implementation Guide</li>
<li>Amended Concepts page to reflect details of key concepts relating to the Encounter Management System and the Clinical Decision Support System</li>
<li>Updated Interactions page to reflect use of term ‘Result’ rather than ‘Disposition’ and also to define a system user more clearly</li>
<li>Updated Interactions page to ensure the descriptive text better aligns with the diagrams</li>
<li>Added additional errors for Payload business rules to API general guidance page</li>
<li>Updated Security page to reflect use of Health and Social Care Directory as the NHS Digital Authorisation server</li>
<li>Updated Security page diagram to reflect actions by Consumer, Provider and Authorisation server</li>
<li>Made inclusion of reference to patient non-mandatory in the <code>ServiceDefinition.$evaluate</code> operation</li>
<li>Added guidance on creation of resources on Questionnaire/Response page</li>
<li>Updated structure of Result page to reflect the three main outcomes of a triage journey more clearly</li>
<li>Updated <code>GuidanceResponse.outputParameters</code> guidance on <code>GuidanceResponse</code> page to reflect detail of how this element carries the state of the patient triage</li>
<li>Updated <code>GuidanceResponse.dataRequirement</code> guidance on <code>GuidanceResponse</code> page to reflect different evaluation scenarios</li>
<li>Added section on Time Out to the General API Guidance page</li>
<li>Updated guidance ‘SHALL’ to ‘MUST’</li>
<li>Updated <code>ServiceDefinition</code> implementation guidance page to define concepts carried in a <code>ServiceDefinition</code></li>
<li>Removed References section from resource implementation guidance and interactions pages</li>
<li>Removed Assurance page from Implementation Guide and added Assurance as Out of scope on Introduction page</li>
<li>Amended FHIR Resources menu tab to read Resources</li>
</ul>
<h2 id="experimental-2">0.8.0-experimental</h2>
<ul>
<li>Added further guidance relating to the <code>userType</code>, <code>initiatingPerson</code> and <code>recipientPerson</code> parameters for the <code>ServiceDefinition.$evaluate</code> operation.</li>
<li>Removed FHIR API guidance from the menu and moved HTTP responses page</li>
<li>Added recommendations arising from initial review of specification</li>
<li>Updated Result page to reflect revised approach to re-directing to a new <code>ServiceDefinition</code></li>
<li>Updated implementation guidance on <code>GuidanceResponse</code> with revised guidance on population of the <code>dataRequirement</code> element</li>
<li>Removed page outlining implementation guidance on an <code>ActivityDefinition</code></li>
<li>Updated Questionnaire/Response interaction page with sections on <code>QuestionnaireResponse</code> and <code>Observation</code></li>
<li>Added page outlining implementation guidance on <code>QuestionnaireResponse</code></li>
<li>Updated API guidance to reflect amendments relating to Resource not found error</li>
</ul>
<h2 id="experimental-3">0.7.0-experimental</h2>
<ul>
<li>Separated implementation guidance for resources from Interaction pages</li>
<li>Created new menu link for FHIR resources to contain resource implementation guidance</li>
<li>Amended menu titles for Interaction pages to reflect the main interactions</li>
<li>Added updated interactions diagram</li>
<li>Updated security page</li>
<li>Updated general API guidance page</li>
</ul>
<h2 id="experimental-4">0.6.0-experimental</h2>
<ul>
<li>Added implementation guidance for a <code>CarePlan</code></li>
<li>Added implementation guidance for a <code>Questionnaire</code></li>
<li>Added implementation guidance for an <code>ActivityDefinition</code></li>
<li>Added menu link for Result</li>
</ul>
<h2 id="experimental-5">0.5.0-experimental</h2>
<ul>
<li>Added implementation guidance for a <code>ServiceDefinition</code></li>
</ul>
<h2 id="experimental-6">0.4.0-experimental</h2>
<ul>
<li>Added further details to <code>GuidanceResponse</code> status element section</li>
<li>Added further details relating to use of <code>RequestGroup</code> to GuidanceResponse page</li>
<li>Added Triage recommendation page</li>
<li>Added initial details to Care Advice recommendation page</li>
<li>Added initial details to Redirect Service Definition page</li>
<li>Added <code>ProcedureRequest</code> section to Triage recommendation page</li>
</ul>
<h2 id="experimental-7">0.3.0-experimental</h2>
<ul>
<li>Added API guidance relating to security and use of JSON Web Tokens</li>
<li>Removed API guidance relating to Parameters pending further research on their implementation in the CDS context</li>
<li>Added further API guidance relating to resource URLs and http verbs</li>
<li>Added further API guidance relating to http headers</li>
</ul>
<h2 id="experimental-8">0.2.0-experimental</h2>
<ul>
<li>Added further API guidance relating to Unknown resource error scenarios</li>
<li>Added further API guidance relating to Parameters</li>
<li>Updated IN Parameters on POST <code>ServiceDefinition</code> page with CDS specific implementation guidance</li>
<li>Added detailed implementation guidance for a <code>GuidanceResponse</code></li>
</ul>
<h2 id="experimental-9">0.1.0-experimental</h2>
<p>Initial draft of the implementation guide</p>

