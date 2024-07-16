---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

sections:
  - block: hero
    content:
      title: Damla & Endre
      text: 👋 Welcome to our wedding website! 👋
      announcement:
        text: 
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: lupines.jpg
          filters:
            brightness: 0.2
  - block: cta-image-paragraph
    id: schedule
    content:
      items:
        - title: Program
          feature_icon: check
          features: 
            - "Our wedding starts on the 20th of July, and lasts until the morning on the 21st of July."
            - "The ceremony starts at 17 o'clock, in the garden of the Panorama Hotel."
          image: RO_invite.jpeg
          design:
            css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-image-paragraph
    id: venue
    content:
      items:
        - title: Venue
          text: ⭐ Panorama Boutique Hotel ⭐
          feature_icon: check
          features:
            - "Address: Calea Valcele, DN13E 9, Sfântu Gheorghe 527175"
            - "[See here the Google maps link📍](https://maps.app.goo.gl/1Afw4j53wqjFV3YF7)"
            - "Website: http://www.panoramacenter.ro/"
            - "Note: the venue is outside of Sepsiszentgyörgy, therefore we recommend staying overnight at one of the other accommodation alternative."
          # Upload image to `assets/media/` and reference the filename here
          image: panorama1.jpg
          button:
            text: How to get there & around
            url: /sepsi/travel
          design:
            css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-image-paragraph
    id: accommodation
    content:
      items:
        - title: Accommodation
          text: 🛏️ These are some possible websites with accommodation option in Sepsiszentgyörgy. It is a fairly small town, with walking distance to pretty much everywhere (except the wedding venue). Nevertheless, most restaurants, bars, and so on are in the center, so consider staying around there.
          feature_icon: check
          features:
            - "[trivago.ro](https://www.trivago.ro/en-US/lm?search=200-66808%3Bdr-20240719-20240721%3Brc-2-2)"
            - "[travelminit.ro](https://travelminit.ro/en/accommodation/sepsiszentgyorgy?ci=2024-07-19&co=2024-07-21)"
            - "[booking.com](https://www.booking.com/searchresults.de.html?ss=Sepsiszentgy%C3%B6rgy%2C+Kov%C3%A1szna+megye%2C+Rom%C3%A1nia&ssne=Bukarest&ssne_untouched=Bukarest&label=gen173nr-1FCAEoggI46AdIB1gEaMABiAEBmAEHuAEHyAEM2AEB6AEB-AECiAIBqAIDuAK29pusBsACAdICJDk1NGQ1Y2ZjLTM2ZWMtNGVmNi1hNjgyLTI3NTVlZWUxZDQ4NdgCBeACAQ&aid=304142&lang=de&sb=1&src_elem=sb&src=index&dest_id=-1170186&dest_type=city&ac_position=0&ac_click_type=b&ac_langcode=hu&ac_suggestion_list_length=2&search_selected=true&search_pageview_id=7d156c1bd032005d&ac_meta=GhA3ZDE1NmMxYmQwMzIwMDVkIAAoATICaHU6BlNlcHNpc0AASgBQAA%3D%3D&checkin=2024-07-19&checkout=2024-07-21&group_adults=1&no_rooms=1&group_children=0&sb_travel_purpose=leisure)"
            - "[airbnb.com](https://www.airbnb.com/s/Sf%C3%A2ntu-Gheorghe--Covasna-County--Romania/homes?tab_id=home_tab&refinement_paths%5B%5D=%2Fhomes&flexible_trip_lengths%5B%5D=one_week&monthly_start_date=2024-01-01&monthly_length=3&price_filter_input_type=0&channel=EXPLORE&query=Sf%C3%A2ntu%20Gheorghe%2C%20Covasna%20County&place_id=ChIJ64pejL6ktEAR7lOCjtjuY68&date_picker_type=calendar&checkin=2024-07-19&checkout=2024-07-21&source=structured_search_input_header&search_type=autocomplete_click)"
          # Upload image to `assets/media/` and reference the filename here
          image: szentgyorgy-bazar.jpg
          design:
            css_class: "bg-gray-100 dark:bg-gray-900"
  - block: markdown
    id: photos
    content:
      title: Photos
      text: |-
        - ☆ We would grately appreciate if you could share your photos with us! ☆
        - ☆ We will share a selection with all guests after the event. ☆
        - <br>
        - <a href="https://www.dropbox.com/request/Mrt6o971jFehHJscqq92" target="_blank" style="display: block; margin: 0 auto; padding: 10px 20px; font-size: 16px; color: #fff; background-color: #007bff; border: none; border-radius: 5px; text-decoration: none; width: fit-content;">Please upload them here</a>
  - block: markdown
    id: taxi
    content:
      title: Taxi
      text: |-
        You can call a taxi at one of these numbers:
        - 📞 [+40745161969](call:+40745161969) 
        - 📞 [+40740439999](call:+40740439999)
        - 📞 [+40723484060](call:+40723484060) 
        - 📞 [+40744839707](call:+40744839707)
        - 📞 [+40722271903](call:+40722271903)
  - block: markdown
    id: contact
    content:
      title: Contact
      text: |-
        You can get in touch with us at:
        - 📧 [damlaendre@gmail.com](email:damlaendre@gmail.com)
        - 📞 Endre Borbáth: [+49 1516 8744 123](call:+4915168744123)
        - 📞 Zsuzsánna-Ella Borbáth: [+40 758 236 181](call:+40758236181)
---
