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
      title: Damla és Endre
      text: 👋 Üdvözlünk esküvőnk honlapján! 👋
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
            - "Az esküvőnk 2024. július 20-án lesz és július 21-én reggelig tart."
            - "A ceremónia 17 órától kezdődik, a Panoráma Hotel kertjében."
          image: RO_invite.jpeg
          design:
            css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-image-paragraph
    id: venue
    content:
      items:
        - title: Helyszín
          text: ⭐ Panorama Boutique Hotel ⭐
          feature_icon: check
          features:
            - "Cím: Calea Valcele, DN13E 9, Sfântu Gheorghe 527175"
            - "Honlap: http://www.panoramacenter.ro/"
            - "Megjegyzés: a helyszín Sepsiszentgyörgyön kívül, Előpatak közelében van, ezért javasoljuk a többi szálláshely valamelyikét."
          # Upload image to `assets/media/` and reference the filename here
          image: panorama1.jpg
          button:
            text: Google maps link📍
            url: https://maps.app.goo.gl/1Afw4j53wqjFV3YF7
          design:
            css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-image-paragraph
    id: accommodation
    content:
      items:
        - title: Szálláshely
          text: 🛏️ Néhány lehetséges weboldal szálláslehetőséggel Sepsiszentgyörgyön&#58; 
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
      title: Fotók
      text: |-
        - ☆ Nagyon értékelnénk ha megosztod fotóid velünk! ☆
        - ☆ Az esemény után küldünk egy válogatást minden vendégnek. ☆
        - <br>
        - <a href="https://www.dropbox.com/request/Mrt6o971jFehHJscqq92" target="_blank" style="display: block; margin: 0 auto; padding: 10px 20px; font-size: 16px; color: #fff; background-color: #007bff; border: none; border-radius: 5px; text-decoration: none; width: fit-content;">Itt tudod őket feltölteni.</a>
  - block: markdown
    id: contact
    content:
      title: Elérhetőség
      text: |-
        A következő módokon léphetsz kapcsolatba velünk:
        - 📧 [damlaendre@gmail.com](email:damlaendre@gmail.com)
        - 📞 Endre: [+49 1516 8744 123](call:+4915168744123)
        - 📞 Zsuzsa: [+40 758 236 181](call:+40758236181)

---