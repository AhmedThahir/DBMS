- Subscriber
  collapsed:: true
  removes partial dependency of everything
	- **_SID_**
	  id:: 6254f3f2-35fc-47b3-8174-c2da7c45a604
	- DOB
	- Name
	- City
	- Company
	- Phone (Landline)
	- Email
	- Industry
	- IndiaPhoneNumber
	- IndiaStreet
	- IndiaDoorNo
- UAEMobile
  collapsed:: true
  because some people have multiple uae mobile numbers
	- ((6254f3f2-35fc-47b3-8174-c2da7c45a604))
	- Mobile
- Dependence (relation)
  collapsed:: true
  removes transitive dependency SID $\to$ dependent name $\to$ dependentGender and Relation
	- ((6254f3f2-35fc-47b3-8174-c2da7c45a604))
	- dependentName
	- dependentGender
	- Relation
- SubscriptionsForKWA
  collapsed:: true
  each person will have multiple payments
	- ((6254f3f2-35fc-47b3-8174-c2da7c45a604))
	- Year
	- Amount
- Applicant
  collapsed:: true
	- _**Email**_
	  because each person can only apply once anways
	- Timestamp
	- Name
	- Profession
	- Years
	- inUAE? (Boolean)
	- CV
	- CommentsReferences
	- GoogleGroups(Boolean)