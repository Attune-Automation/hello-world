# Create Blueprint
Create a new `Blueprint` and include a description.

* Create an `Execute Windows Script` Step in the Blueprint.
* Create Parameters:
    * `Windows Node`
    * `Windows Credentials`
* Populate the newly created parameters into the Step.
* Populate the Script: `Write-Host "Hello, World!"`.
* Write a comment for the Step.

# Create Plan
After you've completed creating the Blueprint, navigate to Plan. 
Create a `Plan Tree`.
* Create a Plan
* Create Values for your Parameters:
    * `Windows Node`
    * `Windows Credentials`
* Populate the Values into the Plan

# Run Job
Once the Plan is populated, navigate to Run. `Run` the Job.