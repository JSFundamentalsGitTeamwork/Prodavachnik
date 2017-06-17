# Prodavachnik

## Description
*Prodavachnik* is a simple web application for personal ads.

## Overview
Stage | HTML/CSS | Front-end | Back-end
--- | --- | --- | ---
Document base | Document base, Login section, Register section | Navigation (view switching)
Styles and Users | Create CSS, Add element classes | Login request, Register request, Session storage | Users collection, Login endpoint, Register endpoint
Load Advertisements | Adverts section | Load ads request, API key constants + change | Advert collection, Load ads endpoint
Branch into Notifications | Notification section, User greeting | AJAX notifications, User in session, Display user greeting
Branch into Create-Edit-Ads | Create ad section, Edit ad section, Ad actions in list | Create ad request, Delete ad request, Edit ad request, Ad actions in list | User info endpoint, Create ad endpoint, Edit ad endpoint, Delete ad endpoint
Branch into Detailed-View | Details section, Ad actions in list | Include ad description, Include ad image, Load single ad request, Ad actions in list | Include ad description to collection, Include ad image to collection, Load single ad endpoint
Cleanup and merge into Master | Add ad description, image to create, edit sections; Merge actions | Add notifications and error handling to create, edit, delete; Add description, image to create and edit | Add description, image to ad create/edit endpoints
