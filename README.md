3D Monitoring Farming System


## Project Description

Σύστημα με το οποίο ο χρήστης μπορεί να κάνει monitoring την καλλιέργεια με σκοπό την αποδοτική και αποτελεσμάτικη διαχείρηση του νερού. Το σύστημα αποτελέιται από ένα Δίκτυο Αισθητήρων ( WSN ) το οποίο είναι τοποθετημένο στην καλλιέργεια και μέσω Application ο χρήστης μπορεί να εποπτεύει την κατάσταση της απομακρυσμένα. 
Μέσω της εφαρμογής ο χρήστης έχει τις παρακάτω δυνατότητες :
  - Δημιουργία 3D απεικόνισης/προσομοίωσης του κτήματος.
  - Διαίρεση του κτήματος σε ζώνες ( ανά γραμμές,στήλες ή γκρουπ δέντρων { 1,2,4 } )
 [![photo-2.png](https://i.postimg.cc/FRmx8JLk/photo-2.png)](https://postimg.cc/WDWrJzSs)
  - Διαχείριση της κάθε ζώνης ανεξάρτητα  
   [![first.png](https://i.postimg.cc/KzVykVPG/first.png)](https://postimg.cc/phDS3sc4)

  - Επιλογή μεταξύ Manual και Automatic ποτίσματος σε κάθε ζώνη.
  - Προσθήκη αισθητήρων σε κάθε ζώνη για τον καλύτερο έλεγχο της κατάστασης της.
  - Ενημέρωση του χρήστη για την κατάσταση της καλλιέργειας όπως :
    - Συνδεδεμένος/Αποδυνδεδεμένος Υποκόμβος.
    - Σύνδεση Νέου Υποκόμβου.
    - Ενεργοποίηση/Απενεργοποίηση Ποτίσματος.
# Getting Started
## Prerequisites

### FrontEnd
 - Embarcadero RAD Studio 10.2 Tokyo

### BackEnd
 - Python 2.7.0
 - MySQL

### WSN:
  - [Raspberry pi 3 Model B]
  - [Soil Humidity YL-69]
  - [DHT adafruit library]
  - [Adafruit unified sensor library]


[Raspberry pi 3 Model B]: <https://www.raspberrypi.org/>
[Soil Humidity YL-69]: <https://grobotronics.com/soil-humidity-sensor.html>
[DHT adafruit library]: <https://github.com/adafruit/DHT-sensor-library>
[Adafruit unified sensor library]: <https://github.com/adafruit/Adafruit_Sensor>
