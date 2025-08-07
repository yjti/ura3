# ura3

Upcoming Exhibition: Toa Payoh Hub
Exhibition Dates: 9 Aug - 17 Aug
Calendar Displays Up to: 19 Aug

How to update the events.json:

{
  "cutoffDate": "2025-08-20",
  "events": [
    {
      "title": "Waves of Wellness @ Marina Central",
      "description": "Join Waves of Wellness 2025 in Marina Central for two weeks of free workouts, crafts and a special Stride & Seek Game.",
      "image": "event-pictures/event1.jpeg",
      "qr": "event-qr/qr1.png",
      "soldOutQr": "event-qr/qr-sold-out.png",
      "date": "2025-07-19",
      "endDate": "2025-08-09",
      "type": "Activity", 
      "status": "available" 
    },

1. Change the cutoffDate to the exhibition end date + 3 days
2. When an event has a change in status, update accordingly: This field is caps sensitive
    1. available: This will display the eventQR and a green tag
    2. information: This will dispaly the eventQR and a green tag (to be used for non-sign up events)
    3. sold-out: This will display the sold-out-QR and a red tag
    4. waitlist: This will display the eventQR and a yellow tag
    5. remove: This will remove events
