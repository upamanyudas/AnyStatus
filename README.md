# AnyStatus - OS X Menubar Internet Status Indicator
The WiFi indicator on the menubar can be misleading. Even though it says you're connected to WiFi, doesn't always mean you're connected to the internet. This is especially true when on train/flight/hotel WiFi.

**AnyStatus** indicates the Internet connectivity status in the OS X menu bar, with a green or a red dot on the menu bar.

![](https://github.com/ajot/menubar-wifi-status/blob/master/assets/demo.gif)

AnyStatus is a fork of [AnyMint](https://github.com/ajot/menubar-wifi-status/) - a tiny Mac app that does one simple thing: it displays a colored dot on the menubar. What the dot means and when to change it is up to you.

AnyStatus simply changes the color of the dot (green or red) by checking if you're truly connected to the internet.

## Setup AnyStatus

1. Install AnyBar
```
brew install --cask anybar
```

2. Clone this repo to the Applications folder
```
cd /Applications/; sudo git clone https://github.com/upamanyudas/AnyStatus.git
```

3. Install dependencies
```
cd AnyStatus; sudo bundle install
```

4. Open System Preferences → Users and Groups → Login items and add  `AnyStatus.app`.

## First Launch
Launch `/Applications/AnyStatus/AnyStatus.app`

Enjoy!
