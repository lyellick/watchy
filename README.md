# ⌚ watchy
All things developed on the [sqfmi watchy e-ink smartwatch](https://watchy.sqfmi.com/).

# 📝 Findings/Notes
- The [docs](https://watchy.sqfmi.com/docs/getting-started#simple-watchface-example) describes `sqfmi/Watchy @ 1.4.1` in `lib_deps`, but will cause build issues. It is better to check [library](https://registry.platformio.org/libraries/sqfmi/Watchy) version for the most recent version. 
- Change military time to standard time and vice versa [here](https://github.com/sqfmi/Watchy/blob/c3587d04a7c2269ad9daadd5472f0ed37467ca5a/src/config.h#L69).
