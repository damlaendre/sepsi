---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Damla and Endre
      text: 👋 Welcome to our wedding website! 👋
      primary_action:
        text: RSVP
        url: https://forms.gle/2Eq7oZhvQa5VHxc87/
        icon: calendar-days
      announcement:
        text: At this stage, we ask you to take note of the date and 
        link:
          text: RSVP
          url: https://forms.gle/2Eq7oZhvQa5VHxc87/
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
  - block: markdown
    id: schedule
    content:
      title: Wedding Schedule
      text: The wedding will take place on Jul. 20, and last until the morning of Jul. 21st, 2023. More details will follow.
  - block: cta-image-paragraph
    id: venue
    content:
      items:
        - title: Wedding Venue
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
          image: szobor-sepsiszentgyorgy.jpg
          design:
            css_class: "bg-gray-100 dark:bg-gray-900"
  - block: markdown
    id: contact
    content:
      title: Contact
      text: You can get in touch with us at [damlaendre@gmail.com](email:damlaendre@gmail.com), or at [+4915168744123](call:+4915168744123)
  
---
