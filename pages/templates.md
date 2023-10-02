- added to the favourites
- patient
  template:: patient
  template-including-parent:: false
	- _dbirth:: 
	  _ddeath::
	  national_of:: 
	  residency::
	  occupation:: 
	  gender::
	- # medical hx
	- # previous medication
	- # admissions to ICU
- admission to ICU
  template:: admission
  template-including-parent:: false
	- _dadmission::
	  _ddischarge::
	  location::
	  reason_for_admission::
	  outcome::
	- # dx during ICU stay
	- # procedures during ICU stay
	- # imaging
	- # lab
	- # complications
- medical dx
	- icd-10::
	  alias::
	  system::
	  template:: dx
-