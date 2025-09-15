Record Type Bypass on Lightning
This is an Example component that allows the automatic selection of a Record Type (based on some criteria), and thus skipping the Record Type selection form. There is a second example component that doesn't skip the Record Type selection, but pre-populates a field when creating a new object.

Note: this example applies this logic to the "New" button on the Campaign related list to a custom object called EventPartnerAccount__c which do not have a Tab. For the second component, it is related with the custom object Submission__c.

Installation
Simply copy the content of the repository to your working project.

Content
First component:

Lightning Aura Component OverrideRTSelectionEvtPrtnAcctCmp
Apex Class OverrideRTSelectionController
Apex Test Class OverrideRTSelectionController_Test
Second component:

Lightning Aura Component OverrideSubmissionAccountCmp
Apex Class OverrideSubmissionAccountController
Apex Test Class OverrideSubmissionAccountControllerTest