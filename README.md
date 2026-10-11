# 🔋 iPhone 13 mini Battery Guide

A practical guide to getting the most out of the iPhone 13 mini's battery, from simple settings anyone can change to more advanced automations.

> ℹ️ **Heads up:** menu names and paths can shift slightly between iOS versions. This guide was written on iOS 27. If a setting isn't where it says, use the search bar at the top of the Settings app.

## 🧭 How to use this guide

The tips are split into three tiers. Start at the top and go as far as you like.

| Tier | What it covers | Effort |
|------|----------------|--------|
| 1. Basics | Settings that cost you nothing | 5 minutes |
| 2. Charging habits | Slowing down battery aging | Ongoing habit |
| 3. Advanced | Automations and background tuning | 15+ minutes |

Not every tip will make a dramatic difference on its own. Battery life comes from many small savings adding up, so treat this as a menu and not a checklist.

---

## ⚙️ Tier 1: Basics

### Check your battery health first
Go to **Settings > Battery > Battery Health & Charging**. Maximum Capacity shows how much of the original capacity your battery still holds. If it has dropped well below 80%, no setting will fully fix poor battery life. A battery replacement is the real solution at that point.

### Find what's draining your battery
- **Settings > Battery**

Apple's battery screen shows each app's share of usage, with labels that explain why: Background Activity, Location, Home & Lock Screen (the display woken by notifications), and No Cell Coverage / Low Signal. Then fix the biggest offenders: limit Background App Refresh or Location for that app, turn off its notifications, or use Airplane Mode in low signal. Usage isn't shown while the phone is charging.

### Use Dark Mode, dark apps and a mostly black wallpaper
The 13 mini has an OLED display, where black pixels use almost no power. Pick a wallpaper that is mostly pure black (#000000) with some detail, and switch on dark or OLED themes in the apps that offer them. True black saves more than dark grey, which still lights the pixels. It only helps while the screen is on. A Purdue study of Android OLED phones found Dark Mode saved only 3% to 9% of power at 30% to 50% brightness, but 39% to 47% at full brightness, so keeping brightness low matters more.

- **Settings > Display & Brightness > Dark**

### Cut back on 5G (LTE or 5G Auto)
5G uses more power than LTE. In a Wall Street Journal test, an iPhone 13 mini lasted about 1.5 hours longer on LTE than on 5G while streaming video. 5G Auto trims some of that cost by using 5G only when it's worth it, but it still uses 5G part of the time, so LTE should save slightly more if you don't need 5G speeds. I couldn't find a direct 5G Auto versus LTE test, so the gap is probably smaller than the 5G versus LTE gap. Pick LTE if you never miss the speed, or 5G Auto if your LTE is weak or slow.

- **Settings > Cellular > Cellular Data Options > Voice & Data**

### Tighten Location Services
Many apps ask for more location access than they need. Set apps to **While Using** or **Never** unless they genuinely need background access (navigation apps, for example). For apps that only need your general area, turn off **Precise Location**.

- **Settings > Privacy & Security > Location Services**

### Other quick wins
- **Auto-Brightness** (Settings > Accessibility > Display & Text Size) is a sensible default. Setting brightness low by hand can save more if you keep it low, since the screen is one of the biggest power draws. Lowering brightness is the biggest display lever: the same study found that going from 100% to 50% cuts the display's own power draw roughly tenfold.
- **Turn off Raise to Wake** (Settings > Display & Brightness) if you find the screen lighting up when you don't need it.
- **Trim notifications.** Each notification wakes the screen. Turn them off for apps you don't need alerts from.
- **Prefer Wi-Fi to cellular** when it's available, since it generally uses less power.
- **Shorten Auto-Lock** (Settings > Display & Brightness > Auto-Lock) to 30 seconds or 1 minute so the screen doesn't stay on after you put the phone down.
- **Keep iOS updated** (Settings > General > Software Update). Apple says updates often include energy-saving technologies.
- **Turn off keyboard haptics** (Settings > Sounds & Haptics > Keyboard Feedback > Haptic). Apple says they may affect battery life, though not by how much.

### Make Low Power Mode a habit
Low Power Mode cuts background activity such as mail fetching and background refresh, trims some visual effects and shortens Auto-Lock to 30 seconds. Some people keep it on all day, and one user reported still having about 50% left by 6pm with it always on. The trade-off is slower mail and delayed background updates.

- For one-tap control, add Low Power Mode to Control Center (Settings > Control Center). Some people also put a Shortcuts toggle on the Lock Screen.
- iOS turns it off by itself after charging past about 80%, so keeping it on all day needs an automation (see Tier 3).

---

## 🔌 Tier 2: Charging habits

### Leave Optimized Battery Charging on
It is on by default. Optimized Battery Charging learns your daily routine and tries to reduce the time your phone spends fully charged, while aiming to be at 100% when you usually unplug.

- **Settings > Battery > Battery Health & Charging > Optimized Battery Charging**

> ⚠️ **Important:** the iPhone 13 mini does **not** have a true charge limit. The hard 80% Charge Limit setting exists only on iPhone 15 models and later. On the 13 mini, if you see a message about charging to 80%, that is Optimized Battery Charging pausing at 80% and finishing to 100% later. It does not stop there permanently.

### Optional: unplug around 80%
Some people unplug at about 80% when they're awake and nearby. Lower charge levels put less stress on a lithium-ion cell, so this may reduce wear over time. The trade-off is less battery on hand, and how much it helps in practice is debated. In one MacRumors long-term test, a phone kept at an 80% limit held 94% capacity after 299 cycles, versus roughly 87% to 90% for phones without a limit. That's a small difference from one person's test. Treat it as an optional habit rather than a requirement.

### Keep it cool
Heat is the biggest enemy of a lithium-ion battery.

- Don't charge the phone under a pillow, in a thick case that traps heat, or in a hot car.
- Take the case off if the phone feels warm while charging.
- Apple's comfort zone is 16° to 22° C (62° to 72° F). Above 35° C (95° F) can permanently reduce battery capacity, while cold only reduces battery life temporarily.
- Avoid leaving the phone in direct sun or in very cold conditions.

### Consider slower charging
Faster chargers generate more heat during charging, and heat is what ages the battery. Using a slow 5W charger for routine or overnight charging keeps the phone cooler. You trade speed for less heat. Keep a faster charger around for the days you need a quick top-up.

### Wired charging runs cooler than wireless
Wireless charging, MagSafe included, loses more energy as heat than a cable does. A "wired MagSafe" doesn't exist: magnetic battery packs and battery cases still charge the phone wirelessly. For long days out, a power bank with a cable is the cooler option. A MagSafe battery pack or battery case is more convenient and still helps, but expect more warmth.

### Avoid draining to 0%
Regularly running the battery completely flat is harder on it than shallower charge cycles. Topping up during the day is fine. If you're storing a phone for months, Apple recommends leaving it at about 50% charge, powered off, in a cool place.

---

## 🛠️ Tier 3: Advanced

### Reduce background activity
Apps that refresh in the background wake the phone and use power.

**Background App Refresh**
- **Settings > General > Background App Refresh**
- Turn it off for apps that don't need to update when you're not using them, or set it to Wi-Fi only. Some people turn it off for everything and say the phone works about the same, with apps updating only when opened.

**Mail fetch settings**
- **Settings > Mail > Mail Accounts > Fetch New Data**
- Push delivers mail as it arrives and can be efficient for accounts that support it. For accounts that rely on Fetch, a longer interval or **Manually** uses the least power, at the cost of delayed mail.

### Automate Low Power Mode with Shortcuts
The Shortcuts app can switch Low Power Mode on for you. Shortcuts does not have a true "phone is idle" trigger, so use one of these instead:

- **Sleep Focus:** turn Low Power Mode on when your Sleep Focus begins.
- **Time of Day:** turn it on at a set time each evening.
- **Battery Level:** turn it on automatically when the battery drops below a level you choose (for example, 30%).
- **Charger:** run an automation when the phone is plugged in or unplugged.

How to set one up:
1. Open **Shortcuts > Automation > New Automation**.
2. Choose a trigger from the list above.
3. Add the action **Set Low Power Mode > On**.
4. Choose **Run Immediately** so it doesn't ask for confirmation each time.

Two more ideas:
- To keep Low Power Mode on most of the day, pair a Battery Level or Charger-disconnect trigger with **Set Low Power Mode > On**, so it comes back after charging.
- Battery alerts: a Battery Level trigger plus Show Notification can warn you at 40%, 30%, 20% and 10%. That doesn't save battery by itself, but it reminds you to act.

Note that iOS turns Low Power Mode off by itself once the phone charges past about 80%, so an automation that switches it on can be overridden by charging.

### Reduce White Point for an extra-dim screen
- **Settings > Accessibility > Display & Text Size > Reduce White Point**

It reduces the intensity of bright colors, so the screen can go dimmer than the normal minimum brightness. On an OLED a dimmer screen should draw less power, though the exact savings vary. **Trade-off:** hard to read in sunlight, and a high value combined with minimum brightness can leave the screen too dark to read.

For quick toggling, add it under Settings > Accessibility > Accessibility Shortcut, then triple-click the side button. One user runs it at 60%.

### Night and morning automations
Some people schedule a bedtime automation that turns off Wi-Fi and Bluetooth and turns on Low Power Mode and Airplane Mode, then reverses it at wake-up time (for example, Wi-Fi on and mobile data off at a workplace with good Wi-Fi and poor signal).

- Phones already use little power overnight, so the extra saving over Low Power Mode alone may be small.
- Airplane Mode means no calls, texts or emergency alerts overnight. Alarms still work.
- Check that Shortcuts offers each action you want (Set Airplane Mode, Set Wi-Fi, Set Bluetooth, Set Cellular Data, Set Low Power Mode). A Location Services toggle may not exist.
- Use a Time of Day trigger and choose Run Immediately.

### Fight weak signal
A weak signal makes the cellular radio work harder and drains the battery. Apple recommends Airplane Mode in poor-coverage areas. Some other options:

- **Wi-Fi Calling** (Settings > Phone > Wi-Fi Calling), if your carrier supports it, moves calls onto Wi-Fi where cellular coverage is poor.
- **Wi-Fi-based automation:** a Shortcuts Wi-Fi trigger can switch Airplane Mode on when you join a known network (home or work, say) and off when you leave. Turn Wi-Fi back on in the same automation, since Airplane Mode switches it off.
- **The catch:** in Airplane Mode, normal calls and texts won't reach you over cellular. Wi-Fi Calling and iMessage may still work, depending on your carrier and setup.

### Download offline maps before a trip
- **Maps > your profile picture > Offline Maps > Download New Map**

Download over Wi-Fi first. It helps most in areas with weak signal, where the cellular radio works hard. Navigation still uses GPS and the screen, which are the main drains, so the savings are modest. Maps take up storage.

### Small effects
- **Reduce Motion** (Settings > Accessibility > Motion) cuts screen animations. It's mainly a comfort setting, and its battery effect is small and unproven.
- **Wi-Fi Assist** (Settings > Cellular > Wi-Fi Assist) switches to cellular when Wi-Fi is weak. Turning it off mainly saves mobile data, and its battery effect is unclear.
- **Home screen widgets** get a limited refresh budget from iOS, so removing them saves little. Location-based widgets and Live Activities cost more.

---

## ✅ Quick reference

**Do these first:**
1. Check Battery Health.
2. Dark Mode, a mostly black wallpaper and dark app themes.
3. LTE or 5G Auto.
4. Location Services to While Using or Never.
5. Background App Refresh off for apps that don't need it.
6. Keep the phone cool while charging.

**What doesn't apply to the 13 mini:** the built-in 80% Charge Limit slider (iPhone 15 and newer only) and Adaptive Power (iOS 26, needs iPhone 15 Pro or newer).

## ℹ️ Disclaimer

This guide is based on general lithium-ion battery behavior and Apple's published documentation. Results vary by phone age, battery condition, carrier, and usage. This is not an official Apple resource.

## 🤝 Contributing

Spotted a mistake or have a tweak that helped you? Open an issue or pull request.

## 📄 License

MIT
