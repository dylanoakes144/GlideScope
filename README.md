# Welcome!
![GlideScope banner](https://github.com/dylanoakes144/GlideScope/blob/main/Config/Documentation/resources/Readme%20Banner.png)

GlideScope is a standalone Precision Approach Radar (PAR) display designed for VATSIM Canada. It provides a realistic azimuth and elevation radar for guiding aircraft on final approach using voice instructions.

Using EuroScope’s built-in FSD server, GlideScope connects locally and leverages VATSIM’s Velocity update system, which provides higher-frequency packets than legacy radar updates. This allows GlideScope to achieve a refresh rate of approximately one update per second, which is necessary for issuing precise and continuous guidance during a PAR approach.

GlideScope supports both live network traffic and a built-in simulator for training, practice, and demonstrations. Approaches are fully configurable, including runway latitude/longitude, glidepath angle, decision altitude, and touchdown point. The radar display consists of separate azimuth and elevation scopes, adjustable range scaling, adjustable aircraft trails, and controller transmission timing cues.

Use of GlideScope is not limited to PAR approaches. It may also be used to monitor ILS or RNAV approaches. By receiving position updates at a significantly higher rate than standard radars, GlideScope is well-suited for monitoring spacing between successive aircraft on any approach.

## Downloading GlideScope

To download the latest version, select the **Releases** tab on GitHub and download the most recent release. The download will be provided as a ZIP file. Extract the contents of the ZIP and run the included .exe file. No installation is required.

This repository does not include the source code. At this stage, it contains only approach data (JSON files) and documentation. Precompiled application binaries are available exclusively through the Releases tab. If you create JSON approach files for your local airport, feel free to send them to me. I’m happy to review and include them in this repository so others can use them as well.

## Disclaimer

GlideScope is for flight simulation only, with no affiliation to real-world ATC or the Royal Canadian Air Force.

![Screenshot of GlideScope radar](https://github.com/dylanoakes144/GlideScope/blob/main/Config/Documentation/resources/radar-screen.png)
