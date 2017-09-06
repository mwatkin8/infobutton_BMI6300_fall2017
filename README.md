# InfoButton Assignment for BMI6300 Fall 2017

A mock EHR website coupled with HL7-compliant RESTful requests to OpenInfobutton, along with a display for the OpenInfobutton response.  Grading will be based on the EHR mockup, placement of infobutton/links on the EHR, functional HL7-compliant infobutton RESTful requests, and successful parsing/display of the OpenInfobutton XML/JSON response. 

#Case Vignette

Frank is a 64-year old male with coronary artery disease, who came to his physician’s office with angina symptoms. Having quit smoking at age 50, after 20 years at a pack a week, he seemed to be in excellent health. However, about two years ago he was diagnosed with angina and given a prescription for aspirin (81 mg/day), simvastatin (40 mg/day), and a recommendation for lifestyle change. At that time he started an exercise regimen and a reduced fat diet. Despite these lifestyle changes, six months ago he noted that episodes of chest pain increased to about once or twice per week. These episodes were precipitated by exercise or stress and relieved by rest. But recently the angina episodes have increased to several times per week. Last week a stress echocardiogram demonstrated anterior wall ischemia and a coronary angiography/stenting (PCI) is recommended. 

Treatment guidelines recommend concomitant use of aspirin (81mg/day) and clopidogrel [Plavix] following an angiography where a stent is placed. Frank is at high risk for a clotting event immediately following a stent placement, so clopidogrel is typically initiated with a loading dose of 300 MG one time to reach target blood levels more quickly. Variations in CYP2C19 can alter the metabolism of clopidogrel such that less active drug is present. The physician’s healthcare organization has recently started an initiative to test patients for such variations when patients need to take clopidogrel. The physician would like to follow this recommendation, but she is not sure what test to order and how to interpret the results.

In addition, Frank and his wife are very concerned about his condition, the recommended procedure, and the new medication. They have several questions that were not answered in the appointment.

Consider how infobuttons could help the physician and the patient for the case above. For example, the links could help the physician and the patient with information needs such as:

For the patient:

Education on Frank’s conditions and the upcoming procedure (PCI)
Education on Frank’s medications
For the physician:

Drug reference information (e.g., dosing, side effects, drug interactions) for each of the patient’s medications
Pharmacogenomics recommendations related to clopidogrel
Reference information on the laboratory test for the CYP2C19 enzyme
