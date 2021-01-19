<table border="1"><tr><td><b>Field</b></td><td><b>Value</b></td></tr>
<tr><td>resourceType</td><td>
"ExplanationOfBenefit"
</td></tr>
<tr><td>id</td><td>
"ProfessionalEOBExample1"
</td></tr>
<tr><td>meta.lastUpdated</td><td>
"2020-10-20T14:46:05-04:00"
</td></tr>
<tr><td>meta.source</td><td>
"Organization/PayerOrganizationExample1"
</td></tr>
<tr><td>meta.profile[0]</td><td>"http://hl7.org/fhir/us/carin-bb/StructureDefinition/C4BB-ExplanationOfBenefit-Professional-NonClinician"</td></tr>
<tr><td>identifier[0].type.coding[0].system</td><td>
"http://hl7.org/fhir/us/carin-bb/CodeSystem/C4BBIdentifierType"
</td></tr>
<tr><td>identifier[0].type.coding[0].code</td><td>
#uc
</td></tr>
<tr><td>identifier[0].type.coding[0].display</td><td>
"Unique Claim ID"
</td></tr>
<tr><td>identifier[0].type.text</td><td>
"Indicates that the claim identifier is that assigned by a payer for a claim received from a provider or subscriber"
</td></tr>
<tr><td>identifier[0].system</td><td>
"https://www.upmchealthplan.com/fhir/EOBIdentifier"
</td></tr>
<tr><td>identifier[0].value</td><td>
ProfessionalEOBExample1
</td></tr>
<tr><td>status</td><td>
"active"
</td></tr>
<tr><td>type.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/claim-type"
</td></tr>
<tr><td>type.coding[0].code</td><td>
#professional
</td></tr>
<tr><td>type.text</td><td>
"Professional"
</td></tr>
<tr><td>use</td><td>
"claim"
</td></tr>
<tr><td>patient.reference</td><td>
"Patient/ExamplePatient1"
</td></tr>
<tr><td>billablePeriod.start</td><td>
"2020-08-04"
</td></tr>
<tr><td>billablePeriod.end</td><td>
"2020-08-04"
</td></tr>
<tr><td>created</td><td>
"2020-08-24T00:00:00-04:00"
</td></tr>
<tr><td>insurer.reference</td><td>
"Organization/PayerOrganizationExample1"
</td></tr>
<tr><td>insurer.display</td><td>
"UPMC Health Plan"
</td></tr>
<tr><td>provider.reference</td><td>
"Organization/ProviderOrganization1"
</td></tr>
<tr><td>payee.type.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/payeetype"
</td></tr>
<tr><td>payee.type.coding[0].code</td><td>
#provider
</td></tr>
<tr><td>payee.type.coding[0].display</td><td>
"Provider"
</td></tr>
<tr><td>payee.type.text</td><td>
"Any benefit payable will be paid to the provider (Assignment of Benefit)."
</td></tr>
<tr><td>payee.party.reference</td><td>
"Organization/ProviderOrganization1"
</td></tr>
<tr><td>outcome</td><td>
"complete"
</td></tr>
<tr><td>careTeam[0].sequence</td><td>
1
</td></tr>
<tr><td>careTeam[0].provider.reference</td><td>
"Organization/ProviderOrganization1"
</td></tr>
<tr><td>careTeam[0].role.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/claimcareteamrole"
</td></tr>
<tr><td>careTeam[0].role.coding[0].code</td><td>
#primary
</td></tr>
<tr><td>careTeam[0].role.coding[0].display</td><td>
"Primary provider"
</td></tr>
<tr><td>careTeam[0].role.text</td><td>
"The primary care provider."
</td></tr>
<tr><td>careTeam[1].sequence</td><td>
2
</td></tr>
<tr><td>careTeam[1].provider.reference</td><td>
"Practitioner/Practitioner1"
</td></tr>
<tr><td>careTeam[1].role.coding[0].system</td><td>
"http://hl7.org/fhir/us/carin-bb/CodeSystem/C4BBClaimCareTeamRole"
</td></tr>
<tr><td>careTeam[1].role.coding[0].code</td><td>
#referring
</td></tr>
<tr><td>careTeam[1].role.coding[0].display</td><td>
"Referring"
</td></tr>
<tr><td>careTeam[1].role.text</td><td>
"The referring physician"
</td></tr>
<tr><td>supportingInfo[0].sequence</td><td>
1
</td></tr>
<tr><td>supportingInfo[0].category.coding[0].system</td><td>
"http://hl7.org/fhir/us/carin-bb/CodeSystem/C4BBSupportingInfoType"
</td></tr>
<tr><td>supportingInfo[0].category.coding[0].code</td><td>
#billingnetworkcontractingstatus
</td></tr>
<tr><td>supportingInfo[0].category.coding[0].display</td><td>
"Billing Network Contracting Status"
</td></tr>
<tr><td>supportingInfo[0].category.text</td><td>
"Indicates that the Billing Provider has a contract with the Payer as of the effective date of service or admission."
</td></tr>
<tr><td>supportingInfo[0].code.coding[0].system</td><td>
"http://hl7.org/fhir/us/carin-bb/CodeSystem/C4BBPayerAdjudicationStatus"
</td></tr>
<tr><td>supportingInfo[0].code.coding[0].code</td><td>
#contracted
</td></tr>
<tr><td>supportingInfo[0].code.coding[0].display</td><td>
"Contracted"
</td></tr>
<tr><td>supportingInfo[0].code.text</td><td>
"Indicates the provider was contracted for the service"
</td></tr>
<tr><td>supportingInfo[1].sequence</td><td>
2
</td></tr>
<tr><td>supportingInfo[1].category.coding[0].system</td><td>
"http://hl7.org/fhir/us/carin-bb/CodeSystem/C4BBSupportingInfoType"
</td></tr>
<tr><td>supportingInfo[1].category.coding[0].code</td><td>
#clmrecvddate
</td></tr>
<tr><td>supportingInfo[1].category.coding[0].display</td><td>
"Claim Received Date"
</td></tr>
<tr><td>supportingInfo[1].category.text</td><td>
"Date the claim was received by the payer."
</td></tr>
<tr><td>supportingInfo[1].timingDate</td><td>
"2020-08-24"
</td></tr>
<tr><td>diagnosis[0].sequence</td><td>
1
</td></tr>
<tr><td>diagnosis[0].diagnosisCodeableConcept.coding[0].system</td><td>
"http://hl7.org/fhir/sid/icd-10-cm"
</td></tr>
<tr><td>diagnosis[0].diagnosisCodeableConcept.coding[0].code</td><td>
#I70.249
</td></tr>
<tr><td>diagnosis[0].type[0].coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/ex-diagnosistype"
</td></tr>
<tr><td>diagnosis[0].type[0].coding[0].code</td><td>
#principal
</td></tr>
<tr><td>diagnosis[0].type[0].coding[0].display</td><td>
"Principal Diagnosis"
</td></tr>
<tr><td>diagnosis[0].type[0].text</td><td>
"The single medical diagnosis that is most relevant to the patient's chief complaint or need for treatment."
</td></tr>
<tr><td>diagnosis[1].sequence</td><td>
2
</td></tr>
<tr><td>diagnosis[1].diagnosisCodeableConcept.coding[0].system</td><td>
"http://hl7.org/fhir/sid/icd-10-cm"
</td></tr>
<tr><td>diagnosis[1].diagnosisCodeableConcept.coding[0].code</td><td>
#L97.929
</td></tr>
<tr><td>diagnosis[1].type[0].coding[0].system</td><td>
"http://hl7.org/fhir/us/carin-bb/CodeSystem/C4BBClaimDiagnosisType"
</td></tr>
<tr><td>diagnosis[1].type[0].coding[0].code</td><td>
#secondary
</td></tr>
<tr><td>diagnosis[1].type[0].coding[0].display</td><td>
"secondary"
</td></tr>
<tr><td>diagnosis[1].type[0].text</td><td>
"Required when necessary to report additional diagnoses on professional and non-clinician claims"
</td></tr>
<tr><td>insurance[0].focal</td><td>
"true"
</td></tr>
<tr><td>insurance[0].coverage.reference</td><td>
"Coverage/CoverageEx1"
</td></tr>
<tr><td>item[0].sequence</td><td>
1
</td></tr>
<tr><td>item[0].productOrService.coding[0].system</td><td>
"http://www.ama-assn.org/go/cpt"
</td></tr>
<tr><td>item[0].productOrService.coding[0].code</td><td>
#75710
</td></tr>
<tr><td>item[0].servicedDate</td><td>
"2020-08-04"
</td></tr>
<tr><td>item[0].locationCodeableConcept.coding[0].system</td><td>
"https://www.cms.gov/Medicare/Coding/place-of-service-codes/Place_of_Service_Code_Set"
</td></tr>
<tr><td>item[0].locationCodeableConcept.coding[0].code</td><td>
#21
</td></tr>
<tr><td>item[0].locationCodeableConcept.text</td><td>
"HOSPITAL - INPATIENT HOSPITAL"
</td></tr>
<tr><td>item[0].adjudication[0].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[0].adjudication[0].category.coding[0].code</td><td>
#submitted
</td></tr>
<tr><td>item[0].adjudication[0].category.coding[0].display</td><td>
"Submitted Amount"
</td></tr>
<tr><td>item[0].adjudication[0].category.text</td><td>
"The total submitted amount for the claim or group or line item."
</td></tr>
<tr><td>item[0].adjudication[0].amount.value</td><td>
68.8
</td></tr>
<tr><td>item[0].adjudication[0].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[0].adjudication[1].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[0].adjudication[1].category.coding[0].code</td><td>
#copay
</td></tr>
<tr><td>item[0].adjudication[1].category.coding[0].display</td><td>
"CoPay"
</td></tr>
<tr><td>item[0].adjudication[1].category.text</td><td>
"Patient Co-Payment"
</td></tr>
<tr><td>item[0].adjudication[1].amount.value</td><td>
0.0
</td></tr>
<tr><td>item[0].adjudication[1].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[0].adjudication[2].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[0].adjudication[2].category.coding[0].code</td><td>
#eligible
</td></tr>
<tr><td>item[0].adjudication[2].category.coding[0].display</td><td>
"Eligible Amount"
</td></tr>
<tr><td>item[0].adjudication[2].category.text</td><td>
"Amount of the change which is considered for adjudication."
</td></tr>
<tr><td>item[0].adjudication[2].amount.value</td><td>
34.8
</td></tr>
<tr><td>item[0].adjudication[2].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[0].adjudication[3].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[0].adjudication[3].category.coding[0].code</td><td>
#deductible
</td></tr>
<tr><td>item[0].adjudication[3].category.coding[0].display</td><td>
"Deductible"
</td></tr>
<tr><td>item[0].adjudication[3].category.text</td><td>
"Amount deducted from the eligible amount prior to adjudication."
</td></tr>
<tr><td>item[0].adjudication[3].amount.value</td><td>
0.0
</td></tr>
<tr><td>item[0].adjudication[3].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[0].adjudication[4].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[0].adjudication[4].category.coding[0].code</td><td>
#benefit
</td></tr>
<tr><td>item[0].adjudication[4].category.coding[0].display</td><td>
"Benefit Amount"
</td></tr>
<tr><td>item[0].adjudication[4].category.text</td><td>
"Amount payable under the coverage"
</td></tr>
<tr><td>item[0].adjudication[4].amount.value</td><td>
34.8
</td></tr>
<tr><td>item[0].adjudication[4].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[0].adjudication[5].category.coding[0].system</td><td>
"http://hl7.org/fhir/us/carin-bb/CodeSystem/C4BBAdjudication"
</td></tr>
<tr><td>item[0].adjudication[5].category.coding[0].code</td><td>
#noncovered
</td></tr>
<tr><td>item[0].adjudication[5].category.coding[0].display</td><td>
"Noncovered"
</td></tr>
<tr><td>item[0].adjudication[5].category.text</td><td>
"The portion of the cost of this service that was deemed not eligible by the insurer because the service or member was not covered by the subscriber contract."
</td></tr>
<tr><td>item[0].adjudication[5].amount.value</td><td>
0.0
</td></tr>
<tr><td>item[0].adjudication[5].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[0].adjudication[6].category.coding[0].system</td><td>
"http://hl7.org/fhir/us/carin-bb/CodeSystem/C4BBPayerAdjudicationStatus"
</td></tr>
<tr><td>item[0].adjudication[6].category.coding[0].code</td><td>
#innetwork
</td></tr>
<tr><td>item[0].adjudication[6].category.coding[0].display</td><td>
"In Network"
</td></tr>
<tr><td>item[0].adjudication[6].category.text</td><td>
"Indicates the claim or claim line was paid in network. This does not indicate the contracting status of the provider"
</td></tr>
<tr><td>item[1].sequence</td><td>
2
</td></tr>
<tr><td>item[1].productOrService.coding[0].system</td><td>
"http://www.ama-assn.org/go/cpt"
</td></tr>
<tr><td>item[1].productOrService.coding[0].code</td><td>
#75710
</td></tr>
<tr><td>item[1].servicedDate</td><td>
"2020-08-04"
</td></tr>
<tr><td>item[1].locationCodeableConcept.coding[0].system</td><td>
"https://www.cms.gov/Medicare/Coding/place-of-service-codes/Place_of_Service_Code_Set"
</td></tr>
<tr><td>item[1].locationCodeableConcept.coding[0].code</td><td>
#21
</td></tr>
<tr><td>item[1].locationCodeableConcept.text</td><td>
"HOSPITAL - INPATIENT HOSPITAL"
</td></tr>
<tr><td>item[1].adjudication[0].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[1].adjudication[0].category.coding[0].code</td><td>
#submitted
</td></tr>
<tr><td>item[1].adjudication[0].category.coding[0].display</td><td>
"Submitted Amount"
</td></tr>
<tr><td>item[1].adjudication[0].category.text</td><td>
"The total submitted amount for the claim or group or line item."
</td></tr>
<tr><td>item[1].adjudication[0].amount.value</td><td>
-68.8
</td></tr>
<tr><td>item[1].adjudication[0].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[1].adjudication[1].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[1].adjudication[1].category.coding[0].code</td><td>
#copay
</td></tr>
<tr><td>item[1].adjudication[1].category.coding[0].display</td><td>
"CoPay"
</td></tr>
<tr><td>item[1].adjudication[1].category.text</td><td>
"Patient Co-Payment"
</td></tr>
<tr><td>item[1].adjudication[1].amount.value</td><td>
0.0
</td></tr>
<tr><td>item[1].adjudication[1].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[1].adjudication[2].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[1].adjudication[2].category.coding[0].code</td><td>
#eligible
</td></tr>
<tr><td>item[1].adjudication[2].category.coding[0].display</td><td>
"Eligible Amount"
</td></tr>
<tr><td>item[1].adjudication[2].category.text</td><td>
"Amount of the change which is considered for adjudication."
</td></tr>
<tr><td>item[1].adjudication[2].amount.value</td><td>
-34.8
</td></tr>
<tr><td>item[1].adjudication[2].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[1].adjudication[3].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[1].adjudication[3].category.coding[0].code</td><td>
#deductible
</td></tr>
<tr><td>item[1].adjudication[3].category.coding[0].display</td><td>
"Deductible"
</td></tr>
<tr><td>item[1].adjudication[3].category.text</td><td>
"Amount deducted from the eligible amount prior to adjudication."
</td></tr>
<tr><td>item[1].adjudication[3].amount.value</td><td>
0.0
</td></tr>
<tr><td>item[1].adjudication[3].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[1].adjudication[4].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[1].adjudication[4].category.coding[0].code</td><td>
#benefit
</td></tr>
<tr><td>item[1].adjudication[4].category.coding[0].display</td><td>
"Benefit Amount"
</td></tr>
<tr><td>item[1].adjudication[4].category.text</td><td>
"Amount payable under the coverage"
</td></tr>
<tr><td>item[1].adjudication[4].amount.value</td><td>
-34.8
</td></tr>
<tr><td>item[1].adjudication[4].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[1].adjudication[5].category.coding[0].system</td><td>
"http://hl7.org/fhir/us/carin-bb/CodeSystem/C4BBAdjudication"
</td></tr>
<tr><td>item[1].adjudication[5].category.coding[0].code</td><td>
#noncovered
</td></tr>
<tr><td>item[1].adjudication[5].category.coding[0].display</td><td>
"Noncovered"
</td></tr>
<tr><td>item[1].adjudication[5].category.text</td><td>
"The portion of the cost of this service that was deemed not eligible by the insurer because the service or member was not covered by the subscriber contract."
</td></tr>
<tr><td>item[1].adjudication[5].amount.value</td><td>
0.0
</td></tr>
<tr><td>item[1].adjudication[5].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[1].adjudication[6].category.coding[0].system</td><td>
"http://hl7.org/fhir/us/carin-bb/CodeSystem/C4BBPayerAdjudicationStatus"
</td></tr>
<tr><td>item[1].adjudication[6].category.coding[0].code</td><td>
#innetwork
</td></tr>
<tr><td>item[1].adjudication[6].category.coding[0].display</td><td>
"In Network"
</td></tr>
<tr><td>item[1].adjudication[6].category.text</td><td>
"Indicates the claim or claim line was paid in network. This does not indicate the contracting status of the provider"
</td></tr>
<tr><td>item[2].sequence</td><td>
3
</td></tr>
<tr><td>item[2].productOrService.coding[0].system</td><td>
"http://www.ama-assn.org/go/cpt"
</td></tr>
<tr><td>item[2].productOrService.coding[0].code</td><td>
#75710
</td></tr>
<tr><td>item[2].servicedDate</td><td>
"2020-08-04"
</td></tr>
<tr><td>item[2].locationCodeableConcept.coding[0].system</td><td>
"https://www.cms.gov/Medicare/Coding/place-of-service-codes/Place_of_Service_Code_Set"
</td></tr>
<tr><td>item[2].locationCodeableConcept.coding[0].code</td><td>
#21
</td></tr>
<tr><td>item[2].locationCodeableConcept.text</td><td>
"HOSPITAL - INPATIENT HOSPITAL"
</td></tr>
<tr><td>item[2].adjudication[0].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[2].adjudication[0].category.coding[0].code</td><td>
#submitted
</td></tr>
<tr><td>item[2].adjudication[0].category.coding[0].display</td><td>
"Submitted Amount"
</td></tr>
<tr><td>item[2].adjudication[0].category.text</td><td>
"The total submitted amount for the claim or group or line item."
</td></tr>
<tr><td>item[2].adjudication[0].amount.value</td><td>
68.8
</td></tr>
<tr><td>item[2].adjudication[0].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[2].adjudication[1].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[2].adjudication[1].category.coding[0].code</td><td>
#copay
</td></tr>
<tr><td>item[2].adjudication[1].category.coding[0].display</td><td>
"CoPay"
</td></tr>
<tr><td>item[2].adjudication[1].category.text</td><td>
"Patient Co-Payment"
</td></tr>
<tr><td>item[2].adjudication[1].amount.value</td><td>
0.0
</td></tr>
<tr><td>item[2].adjudication[1].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[2].adjudication[2].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[2].adjudication[2].category.coding[0].code</td><td>
#eligible
</td></tr>
<tr><td>item[2].adjudication[2].category.coding[0].display</td><td>
"Eligible Amount"
</td></tr>
<tr><td>item[2].adjudication[2].category.text</td><td>
"Amount of the change which is considered for adjudication."
</td></tr>
<tr><td>item[2].adjudication[2].amount.value</td><td>
34.8
</td></tr>
<tr><td>item[2].adjudication[2].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[2].adjudication[3].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[2].adjudication[3].category.coding[0].code</td><td>
#deductible
</td></tr>
<tr><td>item[2].adjudication[3].category.coding[0].display</td><td>
"Deductible"
</td></tr>
<tr><td>item[2].adjudication[3].category.text</td><td>
"Amount deducted from the eligible amount prior to adjudication."
</td></tr>
<tr><td>item[2].adjudication[3].amount.value</td><td>
0.0
</td></tr>
<tr><td>item[2].adjudication[3].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[2].adjudication[4].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[2].adjudication[4].category.coding[0].code</td><td>
#benefit
</td></tr>
<tr><td>item[2].adjudication[4].category.coding[0].display</td><td>
"Benefit Amount"
</td></tr>
<tr><td>item[2].adjudication[4].category.text</td><td>
"Amount payable under the coverage"
</td></tr>
<tr><td>item[2].adjudication[4].amount.value</td><td>
34.8
</td></tr>
<tr><td>item[2].adjudication[4].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[2].adjudication[5].category.coding[0].system</td><td>
"http://hl7.org/fhir/us/carin-bb/CodeSystem/C4BBAdjudication"
</td></tr>
<tr><td>item[2].adjudication[5].category.coding[0].code</td><td>
#noncovered
</td></tr>
<tr><td>item[2].adjudication[5].category.coding[0].display</td><td>
"Noncovered"
</td></tr>
<tr><td>item[2].adjudication[5].category.text</td><td>
"The portion of the cost of this service that was deemed not eligible by the insurer because the service or member was not covered by the subscriber contract."
</td></tr>
<tr><td>item[2].adjudication[5].amount.value</td><td>
0.0
</td></tr>
<tr><td>item[2].adjudication[5].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[2].adjudication[6].category.coding[0].system</td><td>
"http://hl7.org/fhir/us/carin-bb/CodeSystem/C4BBPayerAdjudicationStatus"
</td></tr>
<tr><td>item[2].adjudication[6].category.coding[0].code</td><td>
#innetwork
</td></tr>
<tr><td>item[2].adjudication[6].category.coding[0].display</td><td>
"In Network"
</td></tr>
<tr><td>item[2].adjudication[6].category.text</td><td>
"Indicates the claim or claim line was paid in network. This does not indicate the contracting status of the provider"
</td></tr>
<tr><td>item[3].sequence</td><td>
4
</td></tr>
<tr><td>item[3].productOrService.coding[0].system</td><td>
"http://www.ama-assn.org/go/cpt"
</td></tr>
<tr><td>item[3].productOrService.coding[0].code</td><td>
#37228
</td></tr>
<tr><td>item[3].servicedDate</td><td>
"2020-08-04"
</td></tr>
<tr><td>item[3].locationCodeableConcept.coding[0].system</td><td>
"https://www.cms.gov/Medicare/Coding/place-of-service-codes/Place_of_Service_Code_Set"
</td></tr>
<tr><td>item[3].locationCodeableConcept.coding[0].code</td><td>
#21
</td></tr>
<tr><td>item[3].locationCodeableConcept.text</td><td>
"HOSPITAL - INPATIENT HOSPITAL"
</td></tr>
<tr><td>item[3].adjudication[0].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[3].adjudication[0].category.coding[0].code</td><td>
#submitted
</td></tr>
<tr><td>item[3].adjudication[0].category.coding[0].display</td><td>
"Submitted Amount"
</td></tr>
<tr><td>item[3].adjudication[0].category.text</td><td>
"The total submitted amount for the claim or group or line item."
</td></tr>
<tr><td>item[3].adjudication[0].amount.value</td><td>
751.2
</td></tr>
<tr><td>item[3].adjudication[0].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[3].adjudication[1].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[3].adjudication[1].category.coding[0].code</td><td>
#copay
</td></tr>
<tr><td>item[3].adjudication[1].category.coding[0].display</td><td>
"CoPay"
</td></tr>
<tr><td>item[3].adjudication[1].category.text</td><td>
"Patient Co-Payment"
</td></tr>
<tr><td>item[3].adjudication[1].amount.value</td><td>
0.0
</td></tr>
<tr><td>item[3].adjudication[1].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[3].adjudication[2].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[3].adjudication[2].category.coding[0].code</td><td>
#eligible
</td></tr>
<tr><td>item[3].adjudication[2].category.coding[0].display</td><td>
"Eligible Amount"
</td></tr>
<tr><td>item[3].adjudication[2].category.text</td><td>
"Amount of the change which is considered for adjudication."
</td></tr>
<tr><td>item[3].adjudication[2].amount.value</td><td>
224.11
</td></tr>
<tr><td>item[3].adjudication[2].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[3].adjudication[3].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[3].adjudication[3].category.coding[0].code</td><td>
#deductible
</td></tr>
<tr><td>item[3].adjudication[3].category.coding[0].display</td><td>
"Deductible"
</td></tr>
<tr><td>item[3].adjudication[3].category.text</td><td>
"Amount deducted from the eligible amount prior to adjudication."
</td></tr>
<tr><td>item[3].adjudication[3].amount.value</td><td>
0.0
</td></tr>
<tr><td>item[3].adjudication[3].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[3].adjudication[4].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[3].adjudication[4].category.coding[0].code</td><td>
#benefit
</td></tr>
<tr><td>item[3].adjudication[4].category.coding[0].display</td><td>
"Benefit Amount"
</td></tr>
<tr><td>item[3].adjudication[4].category.text</td><td>
"Amount payable under the coverage"
</td></tr>
<tr><td>item[3].adjudication[4].amount.value</td><td>
0.0
</td></tr>
<tr><td>item[3].adjudication[4].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[3].adjudication[5].category.coding[0].system</td><td>
"http://hl7.org/fhir/us/carin-bb/CodeSystem/C4BBAdjudication"
</td></tr>
<tr><td>item[3].adjudication[5].category.coding[0].code</td><td>
#noncovered
</td></tr>
<tr><td>item[3].adjudication[5].category.coding[0].display</td><td>
"Noncovered"
</td></tr>
<tr><td>item[3].adjudication[5].category.text</td><td>
"The portion of the cost of this service that was deemed not eligible by the insurer because the service or member was not covered by the subscriber contract."
</td></tr>
<tr><td>item[3].adjudication[5].amount.value</td><td>
224.11
</td></tr>
<tr><td>item[3].adjudication[5].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[3].adjudication[6].category.coding[0].system</td><td>
"http://hl7.org/fhir/us/carin-bb/CodeSystem/C4BBPayerAdjudicationStatus"
</td></tr>
<tr><td>item[3].adjudication[6].category.coding[0].code</td><td>
#innetwork
</td></tr>
<tr><td>item[3].adjudication[6].category.coding[0].display</td><td>
"In Network"
</td></tr>
<tr><td>item[3].adjudication[6].category.text</td><td>
"Indicates the claim or claim line was paid in network. This does not indicate the contracting status of the provider"
</td></tr>
<tr><td>item[4].sequence</td><td>
5
</td></tr>
<tr><td>item[4].productOrService.coding[0].system</td><td>
"http://www.ama-assn.org/go/cpt"
</td></tr>
<tr><td>item[4].productOrService.coding[0].code</td><td>
#37228
</td></tr>
<tr><td>item[4].servicedDate</td><td>
"2020-08-04"
</td></tr>
<tr><td>item[4].locationCodeableConcept.coding[0].system</td><td>
"https://www.cms.gov/Medicare/Coding/place-of-service-codes/Place_of_Service_Code_Set"
</td></tr>
<tr><td>item[4].locationCodeableConcept.coding[0].code</td><td>
#21
</td></tr>
<tr><td>item[4].locationCodeableConcept.text</td><td>
"HOSPITAL - INPATIENT HOSPITAL"
</td></tr>
<tr><td>item[4].adjudication[0].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[4].adjudication[0].category.coding[0].code</td><td>
#submitted
</td></tr>
<tr><td>item[4].adjudication[0].category.coding[0].display</td><td>
"Submitted Amount"
</td></tr>
<tr><td>item[4].adjudication[0].category.text</td><td>
"The total submitted amount for the claim or group or line item."
</td></tr>
<tr><td>item[4].adjudication[0].amount.value</td><td>
751.2
</td></tr>
<tr><td>item[4].adjudication[0].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[4].adjudication[1].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[4].adjudication[1].category.coding[0].code</td><td>
#copay
</td></tr>
<tr><td>item[4].adjudication[1].category.coding[0].display</td><td>
"CoPay"
</td></tr>
<tr><td>item[4].adjudication[1].category.text</td><td>
"Patient Co-Payment"
</td></tr>
<tr><td>item[4].adjudication[1].amount.value</td><td>
0.0
</td></tr>
<tr><td>item[4].adjudication[1].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[4].adjudication[2].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[4].adjudication[2].category.coding[0].code</td><td>
#eligible
</td></tr>
<tr><td>item[4].adjudication[2].category.coding[0].display</td><td>
"Eligible Amount"
</td></tr>
<tr><td>item[4].adjudication[2].category.text</td><td>
"Amount of the change which is considered for adjudication."
</td></tr>
<tr><td>item[4].adjudication[2].amount.value</td><td>
224.11
</td></tr>
<tr><td>item[4].adjudication[2].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[4].adjudication[3].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[4].adjudication[3].category.coding[0].code</td><td>
#deductible
</td></tr>
<tr><td>item[4].adjudication[3].category.coding[0].display</td><td>
"Deductible"
</td></tr>
<tr><td>item[4].adjudication[3].category.text</td><td>
"Amount deducted from the eligible amount prior to adjudication."
</td></tr>
<tr><td>item[4].adjudication[3].amount.value</td><td>
0.0
</td></tr>
<tr><td>item[4].adjudication[3].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[4].adjudication[4].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[4].adjudication[4].category.coding[0].code</td><td>
#benefit
</td></tr>
<tr><td>item[4].adjudication[4].category.coding[0].display</td><td>
"Benefit Amount"
</td></tr>
<tr><td>item[4].adjudication[4].category.text</td><td>
"Amount payable under the coverage"
</td></tr>
<tr><td>item[4].adjudication[4].amount.value</td><td>
224.11
</td></tr>
<tr><td>item[4].adjudication[4].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[4].adjudication[5].category.coding[0].system</td><td>
"http://hl7.org/fhir/us/carin-bb/CodeSystem/C4BBAdjudication"
</td></tr>
<tr><td>item[4].adjudication[5].category.coding[0].code</td><td>
#noncovered
</td></tr>
<tr><td>item[4].adjudication[5].category.coding[0].display</td><td>
"Noncovered"
</td></tr>
<tr><td>item[4].adjudication[5].category.text</td><td>
"The portion of the cost of this service that was deemed not eligible by the insurer because the service or member was not covered by the subscriber contract."
</td></tr>
<tr><td>item[4].adjudication[5].amount.value</td><td>
0.0
</td></tr>
<tr><td>item[4].adjudication[5].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[4].adjudication[6].category.coding[0].system</td><td>
"http://hl7.org/fhir/us/carin-bb/CodeSystem/C4BBPayerAdjudicationStatus"
</td></tr>
<tr><td>item[4].adjudication[6].category.coding[0].code</td><td>
#innetwork
</td></tr>
<tr><td>item[4].adjudication[6].category.coding[0].display</td><td>
"In Network"
</td></tr>
<tr><td>item[4].adjudication[6].category.text</td><td>
"Indicates the claim or claim line was paid in network. This does not indicate the contracting status of the provider"
</td></tr>
<tr><td>item[5].sequence</td><td>
6
</td></tr>
<tr><td>item[5].productOrService.coding[0].system</td><td>
"http://www.ama-assn.org/go/cpt"
</td></tr>
<tr><td>item[5].productOrService.coding[0].code</td><td>
#37228
</td></tr>
<tr><td>item[5].servicedDate</td><td>
"2020-08-04"
</td></tr>
<tr><td>item[5].locationCodeableConcept.coding[0].system</td><td>
"https://www.cms.gov/Medicare/Coding/place-of-service-codes/Place_of_Service_Code_Set"
</td></tr>
<tr><td>item[5].locationCodeableConcept.coding[0].code</td><td>
#21
</td></tr>
<tr><td>item[5].locationCodeableConcept.text</td><td>
"HOSPITAL - INPATIENT HOSPITAL"
</td></tr>
<tr><td>item[5].adjudication[0].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[5].adjudication[0].category.coding[0].code</td><td>
#submitted
</td></tr>
<tr><td>item[5].adjudication[0].category.coding[0].display</td><td>
"Submitted Amount"
</td></tr>
<tr><td>item[5].adjudication[0].category.text</td><td>
"The total submitted amount for the claim or group or line item."
</td></tr>
<tr><td>item[5].adjudication[0].amount.value</td><td>
-751.2
</td></tr>
<tr><td>item[5].adjudication[0].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[5].adjudication[1].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[5].adjudication[1].category.coding[0].code</td><td>
#copay
</td></tr>
<tr><td>item[5].adjudication[1].category.coding[0].display</td><td>
"CoPay"
</td></tr>
<tr><td>item[5].adjudication[1].category.text</td><td>
"Patient Co-Payment"
</td></tr>
<tr><td>item[5].adjudication[1].amount.value</td><td>
0.0
</td></tr>
<tr><td>item[5].adjudication[1].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[5].adjudication[2].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[5].adjudication[2].category.coding[0].code</td><td>
#eligible
</td></tr>
<tr><td>item[5].adjudication[2].category.coding[0].display</td><td>
"Eligible Amount"
</td></tr>
<tr><td>item[5].adjudication[2].category.text</td><td>
"Amount of the change which is considered for adjudication."
</td></tr>
<tr><td>item[5].adjudication[2].amount.value</td><td>
-224.11
</td></tr>
<tr><td>item[5].adjudication[2].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[5].adjudication[3].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[5].adjudication[3].category.coding[0].code</td><td>
#deductible
</td></tr>
<tr><td>item[5].adjudication[3].category.coding[0].display</td><td>
"Deductible"
</td></tr>
<tr><td>item[5].adjudication[3].category.text</td><td>
"Amount deducted from the eligible amount prior to adjudication."
</td></tr>
<tr><td>item[5].adjudication[3].amount.value</td><td>
0.0
</td></tr>
<tr><td>item[5].adjudication[3].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[5].adjudication[4].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>item[5].adjudication[4].category.coding[0].code</td><td>
#benefit
</td></tr>
<tr><td>item[5].adjudication[4].category.coding[0].display</td><td>
"Benefit Amount"
</td></tr>
<tr><td>item[5].adjudication[4].category.text</td><td>
"Amount payable under the coverage"
</td></tr>
<tr><td>item[5].adjudication[4].amount.value</td><td>
0.0
</td></tr>
<tr><td>item[5].adjudication[4].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[5].adjudication[5].category.coding[0].system</td><td>
"http://hl7.org/fhir/us/carin-bb/CodeSystem/C4BBAdjudication"
</td></tr>
<tr><td>item[5].adjudication[5].category.coding[0].code</td><td>
#noncovered
</td></tr>
<tr><td>item[5].adjudication[5].category.coding[0].display</td><td>
"Noncovered"
</td></tr>
<tr><td>item[5].adjudication[5].category.text</td><td>
"The portion of the cost of this service that was deemed not eligible by the insurer because the service or member was not covered by the subscriber contract."
</td></tr>
<tr><td>item[5].adjudication[5].amount.value</td><td>
-224.11
</td></tr>
<tr><td>item[5].adjudication[5].amount.currency</td><td>
#USD
</td></tr>
<tr><td>item[5].adjudication[6].category.coding[0].system</td><td>
"http://hl7.org/fhir/us/carin-bb/CodeSystem/C4BBPayerAdjudicationStatus"
</td></tr>
<tr><td>item[5].adjudication[6].category.coding[0].code</td><td>
#innetwork
</td></tr>
<tr><td>item[5].adjudication[6].category.coding[0].display</td><td>
"In Network"
</td></tr>
<tr><td>item[5].adjudication[6].category.text</td><td>
"Indicates the claim or claim line was paid in network. This does not indicate the contracting status of the provider"
</td></tr>
<tr><td>total[0].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>total[0].category.coding[0].code</td><td>
#submitted
</td></tr>
<tr><td>total[0].category.coding[0].display</td><td>
"Submitted Amount"
</td></tr>
<tr><td>total[0].category.text</td><td>
"The total submitted amount for the claim or group or line item."
</td></tr>
<tr><td>total[0].amount.value</td><td>
820.0
</td></tr>
<tr><td>total[0].amount.currency</td><td>
#USD
</td></tr>
<tr><td>total[1].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>total[1].category.coding[0].code</td><td>
#eligible
</td></tr>
<tr><td>total[1].category.coding[0].display</td><td>
"Eligible Amount"
</td></tr>
<tr><td>total[1].category.text</td><td>
"Amount of the change which is considered for adjudication."
</td></tr>
<tr><td>total[1].amount.value</td><td>
258.91
</td></tr>
<tr><td>total[1].amount.currency</td><td>
#USD
</td></tr>
<tr><td>total[2].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>total[2].category.coding[0].code</td><td>
#deductible
</td></tr>
<tr><td>total[2].category.coding[0].display</td><td>
"Deductible"
</td></tr>
<tr><td>total[2].category.text</td><td>
"Amount deducted from the eligible amount prior to adjudication."
</td></tr>
<tr><td>total[2].amount.value</td><td>
0.0
</td></tr>
<tr><td>total[2].amount.currency</td><td>
#USD
</td></tr>
<tr><td>total[3].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>total[3].category.coding[0].code</td><td>
#copay
</td></tr>
<tr><td>total[3].category.coding[0].display</td><td>
"CoPay"
</td></tr>
<tr><td>total[3].category.text</td><td>
"Patient Co-Payment"
</td></tr>
<tr><td>total[3].amount.value</td><td>
0.0
</td></tr>
<tr><td>total[3].amount.currency</td><td>
#USD
</td></tr>
<tr><td>total[4].category.coding[0].system</td><td>
"http://hl7.org/fhir/us/carin-bb/CodeSystem/C4BBAdjudication"
</td></tr>
<tr><td>total[4].category.coding[0].code</td><td>
#noncovered
</td></tr>
<tr><td>total[4].category.coding[0].display</td><td>
"Noncovered"
</td></tr>
<tr><td>total[4].category.text</td><td>
"The portion of the cost of this service that was deemed not eligible by the insurer because the service or member was not covered by the subscriber contract."
</td></tr>
<tr><td>total[4].amount.value</td><td>
0.0
</td></tr>
<tr><td>total[4].amount.currency</td><td>
#USD
</td></tr>
<tr><td>total[5].category.coding[0].system</td><td>
"http://terminology.hl7.org/CodeSystem/adjudication"
</td></tr>
<tr><td>total[5].category.coding[0].code</td><td>
#benefit
</td></tr>
<tr><td>total[5].category.coding[0].display</td><td>
"Benefit Amount"
</td></tr>
<tr><td>total[5].category.text</td><td>
"Amount payable under the coverage"
</td></tr>
<tr><td>total[5].amount.value</td><td>
258.91
</td></tr>
<tr><td>total[5].amount.currency</td><td>
#USD
</td></tr>
<tr><td>total[6].category.coding[0].system</td><td>
"http://hl7.org/fhir/us/carin-bb/CodeSystem/C4BBAdjudication"
</td></tr>
<tr><td>total[6].category.coding[0].code</td><td>
#memberliability
</td></tr>
<tr><td>total[6].category.coding[0].display</td><td>
"Member liability"
</td></tr>
<tr><td>total[6].category.text</td><td>
"The amount of the member's liability."
</td></tr>
<tr><td>total[6].amount.value</td><td>
0.0
</td></tr>
<tr><td>total[6].amount.currency</td><td>
#USD
</td></tr>
</table>