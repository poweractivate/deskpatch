Desk Reservation Template July 20 2022
Original by https://github.com/aprildunnam
Check original repo for original / updated version: https://github.com/aprildunnam/PowerApps/tree/master/Desk%20Reservation%20Template

Deployment Instructions
1. Download the Desk Reservation App Zip and the Desk Reservation Provisioner Zip
2. Go to flow.microsoft.com
3. Import the Desk Reservation Provisioner Zip into Power Automate
4. Edit the Action that says "! Enter URL of SP Site to Deploy to here" and put in your SharePoinst site url that you want the underlying list to reside. Keep not of that site URL.

5. Apply patches to Flow blocks from 
https://powerusers.microsoft.com/t5/Webinars-and-Video-Gallery/Desk-Booking-amp-Reservation-Power-Apps-Template/m-p/1680663/highlight/true#M2119

6. Run the "Desk Reservation Provisioner" Flow. This will create the necessary resources in Sharepoint.
7. Go to make.powerapps.com
8. Click on the Apps tabs on the left hand rail
9. Click 'Import Canvas App' in the ribbon and browse to the Desk Booking App Zip File

10. Apply patches to Power App from 
https://powerusers.microsoft.com/t5/Webinars-and-Video-Gallery/Desk-Booking-amp-Reservation-Power-Apps-Template/m-p/1680663/highlight/true#M2119


11. Open the app in edit mode.
12. Click the data connections tab and delete all of the SharePoint Data Connections in the app
13. Search for SharePoint and add in the new SharePoint lists in your tenant that you just provisioned.
