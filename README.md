# ⌚ watchy
All things developed on the [sqfmi watchy e-ink smartwatch](https://watchy.sqfmi.com/).

# 💡 Project Ideas - Watch Faces/Standalone/Apps
- [Just Steps](https://github.com/lyellick/watchy/tree/main/just-steps)
- Maze Genetrator with path finding being the second hand
- JSONStash Integration
- [MicroPython](https://github.com/hueyy/watchy_py) R&D

# 📝 Findings/Notes
- The [docs](https://watchy.sqfmi.com/docs/getting-started#simple-watchface-example) describes `sqfmi/Watchy @ 1.4.1` in `lib_deps`, but will cause build issues. It is better to check the [library](https://registry.platformio.org/libraries/sqfmi/Watchy) version for the most recent version. 
- Change military time to standard time and vice versa [here](https://github.com/sqfmi/Watchy/blob/c3587d04a7c2269ad9daadd5472f0ed37467ca5a/src/config.h#L69).
