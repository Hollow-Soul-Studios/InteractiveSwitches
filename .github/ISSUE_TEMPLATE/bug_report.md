---
name: Bug report
about: Create a report to help us improve
title: '[Bug] '
labels: 'bug'
assignees: ''

---

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

**Expected behavior**
A clear and concise description of what you expected to happen.

**Screenshots**
Please add screenshots to help explain your problem.

**Interactive Switches Version**
 - [ ] v1.0 (engine versions prior to UE 5.8, not network replicated)
 - [ ] v2.0 (UE 5.8, network replicated)

**Unreal Engine Version**
 - UE 4.xx / UE 5.xx (please give the exact version, e.g. 5.8.4)

**Net Mode** (v2.0 only, or if you are using v1.0 in multiplayer)
 - [ ] Standalone / single player
 - [ ] Listen Server, as seen by the host
 - [ ] Listen Server, as seen by a client
 - [ ] Dedicated Server, as seen by a client
 - [ ] Client that joined late (after lights were toggled)
 - [ ] Play In Editor (PIE)
 - [ ] Packaged build

**Setup**
 - Are you using the included `BP_FirstPerson_EXAMPLE`, or your own character? If you use your own character, does it call `Interact` through a Server RPC (see the README's Multiplayer section)?
 - Are your lights Child Blueprints of `BP_Light_Master`?
 - How many lights are assigned to the affected switch?

**Logs**
Please attach any relevant lines from `Saved/Logs/<YourProject>.log`, such as Blueprint runtime errors or `LogNet` warnings.

**Additional context**
Add any other context about the problem here.
