### template
  - Features Added
  - Bugs Fixed
  - Maintenence / Refactor
  - Misc

### Unreleased

  - Features Added
    - Links in proposal description open in new tab
    - Show a message on startup when waiting for subgraph
    - Create a single place where all redemptions can be redeemed
    - Cached provider, when available, is now always used when connecting to one's wallet
    - Nicer layout of the list of DAO cards on mobile devices
    - Hide WalletConnect provider option on mobile devices
    - Shrink wallet providers popup window on mobile devices, so can be cancelled
    - more friendly display of error conditions (404 and uncaught exception errors)
    - List of voters in the Voters Popup now shows the user's friendly name, when available.
    - Don't allow connecting to wrong networks
    - Issue a notification when the user connects to a wrong network
    
  - Bugs Fixed
    - Align headers of table in proposal history
    - Re-add redeem for beneficiary button to proposal details page
    - Fix error on initializing arc
    - Fix infinite scroll loading of queued scheme proposals
    - handle Metamask account changing

### 2019-09-12 [actually two releses]

  - Features Added
    - Tweaks to the wallet provider UI
    - Allow to RedeemFromToken by passing a private key in the URL
    - Use subgraph version 26 in staging
    - Allow for setting subgraph connection with environment variables
    - correct URL form validation
    - fix handling of very small amounts when staking
    - fix handling of very large amounts when displaying proposals
    - fix crash in display of proposals' redeemables when account is readonly
    - show proposals as failing when the vote is tied
    - improvements, bug fixes on the Scheme Information page
    - DAO Discussion page
    - Add link to help center
    - Reduce number of subscriptions from DAO history page
    - add breadcrums to mobile
    - add support for WalletConnect web3 providers
    - add static mint and burn permission 
  - Bugs Fixed
    - Fix number formatting
    - Fix crashing of scheme page
    - Hide notifications after 10 seconds
    - Add dao address as default value for Cross-DAO redemptions
    - Fix redemptions count
    - Display proper message when no history
    - avoid duplicate Genesis Alpha cards
    - fix action button not appearing when proposal card countdown completes


### version 0.9.4; 2019-08-13

  - Improve wallet UX
  - Sharing buttons
  - Fix several redeemer bugs
  - Add unit tests
  - UI fixes
  - Added a change log!
