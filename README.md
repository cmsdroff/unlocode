# unlocode
Proof of Concept around maintenance process (DMR) for UNLOCODE using GitHub

For the Proof of Concept the DMRS are pulled in from the Google Sheet that is already public, for demonstration i have simply pulled additions for all countries from 1 sheet.

They automatically make a code change to the relevant country file against a branch using the UN request ID

This is followed by a pull request which would be sent to a team of reviewers (maintenance team) 

Changes only to be merged by the secretariat for control

# Releases

Use of Tags to prouce an official output (i.e. D22b) this is a snapshot in time same as today.

# Live Feed

For those who want the latest codes once approved they can get them from the `main` branch and be notified on change using Github built in features.
