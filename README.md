# Crowdify: Crowdfunding on solana

Crowdify is a crowdfunding platform supporting native SOL tokens. All information about the campaigns as well as donations to the campaigns are stored securely on chain.

## Features

1. Users can create their own campaign: When creating new campaigns, users must provide the basic campaign related information such as name, description along with three more important campaign properties: target amount, delay, duration. Targt amount is the amount of SOL tokens that the campaign expects to raise. Delay is the amount of hours from current time that campaign will start. All the campaigns that will start immediately after transaction processing, needs to give delay as 0. It allows for scheduling campaigns in future. Duration is simply for how many hours the campaign will run and be live. Only when the campaign is live, other users can donate to it.
2. Users can donate to the ongoing campaigns: Users can see all the campaigns, that are finished, currently running, and that are over, with the ability to donate to ongoing campaigns. Campaigns that reach their target amount goal will only be considered successful and allow withdrawing of funds by the campaign admin. On the other hand, if a campaign fails to meet its target, the users who donated to the campaign can withdraw their SOL back. All
Donate to the campaigns that are currently running.
3. All the users who donate to any campaign receive that campaign's respective SPL tokens to prove that they donated a specific amount to the campaign.

## Dependencies

The app currently supports transactions with phantom wallet. All the users should install phantom wallet extension in their browser, and are expected to have their account logged into the phantom wallet.

### Website: https://crowdefi.netlify.app/
