Here is a short guide on how you can provision meters and meter types for Botbot AI assist.

- 1. Provisioning Meter Types
- 2. Botbot AI assist
- 3. Provisioning Meters
- 4. Purge Meters

Step 1:
Create a new application for your account. This will be used for authenticating with the metering api.

Step 2: 
Create a new secret in secrets wallet of type OAuth 2.0 containing your applications credentials.

Step 3:
Import all example streams.

Step 4:
Update the authentication in all streams with your new secret.

Step 5:
Run stream "1. Provisioning Meter Types". After the stream has completed you will have 6 new meter types in the Usage metering section.

Step 6:
Open the stream configuration of "2. Botbot AI assist" and copy the meter key from the Meter processor for later.

Step 7:
Open the stream configuration of "3. Provisioning Meters" and open the script named "Prepare Meters". Paste in the meter key that you got from the previous step.

Step 8:
Run stream "3. Provisioning Meters". After the stream has completed, you will have 12 meters across your newly created meter types.

Step 9:
The meters you created in the previous step are now associated with the Meter Processor in the "Botbot AI assist" stream.
Run "Botbot AI assist" stream. After its completion, you will be able to see the aggregated values in the inspection tab.

Step 10 (Bonus):
If you want to delete your meters. Run "4. Purge Meters" stream. Now all meters related to "Botbot AI assist" have been deleted.

Happy Metering!