# Workbae-
Landing pages for enquiries for Workbae Coworking Jaipur (https://www.workbaecoworking.com/).

## Pages

### `teams/`: office space for teams in Jaipur
Live at https://www.workbaecoworking.com/teams/. Both Google Ads campaigns send people here.

- `teams/index.html`: the page. It includes Google Tag Manager (GTM-NZZQSLGP) and is set to `noindex`, because it's only for Google Ads visitors.
- `teams/teams-reel.mp4`: the video at the top of the page. It has to stay in the same folder as `index.html`.
- `teams/img/`: the photos and logos. Upload the whole `img` folder next to `index.html`.

## Putting a change live (Hostinger)
1. In Hostinger File Manager, open `public_html/teams/`.
2. Delete the old file, then upload the new `index.html`, the `img` folder, and `teams-reel.mp4` if it changed.
3. Test on a phone. The video should play on mute and the speaker icon should turn sound on and off. Every WhatsApp and Call button should open. These buttons must keep the ids `whatsapp-click` / `phone-click`, because Google Ads counts enquiries through them.
