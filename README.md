# Interbotix

HTML and CSS product pages for Interbotix research robots sold by Trossen Robotics, part of the Trossen Robotics web projects. Covers the X-Series robot arms, LoCoBot mobile manipulators, and ALOHA bimanual teleoperation kits, plus pages for the TurtleBot 4 platform from Clearpath Robotics.

## Products

| Product | Type | Description | Folder |
|---|---|---|---|
| ALOHA | Bimanual teleoperation | Low-cost open-source system for collecting bimanual demonstration data. Trossen kits use ViperX 300 S follower arms and WidowX 250 S leader arms. | `ALOHA/` |
| X-Series Arms | Robot arms | Research arms with 4, 5, or 6 degrees of freedom and working payloads from 50 g (PincherX 100) to 750 g (ViperX 300). ROS and ROS 2 support. | `X-Series Arms/` |
| LoCoBot Base | Mobile base | ROS research rover for mapping and navigation, built on the iRobot Create 3. | `LoCoBots/LoCoBot Base/` |
| LoCoBot PX100 | Mobile manipulator | LoCoBot with the 4-DOF PincherX 100 arm (50 g working payload). | `LoCoBots/LoCoBot PX100/` |
| LoCoBot WX200 | Mobile manipulator | LoCoBot with the 5-DOF WidowX 200 arm (200 g working payload). | `LoCoBots/LoCoBot WX200/` |
| LoCoBot WX250 | Mobile manipulator | LoCoBot with the 6-DOF WidowX 250 arm (250 g working payload). | `LoCoBots/LoCoBot WX250/` |
| LoCoBot PyRobot | Mobile manipulator | Carnegie Mellon LoCoBot built to run PyRobot, with a Kobuki base and WidowX 200 arm. | `LoCoBots/LoCoBot PyRobot/` |
| TurtleBot 4 | Mobile robot | Open-source ROS 2 education and research robot from Clearpath Robotics, built on the iRobot Create 3 with a Raspberry Pi 4. | `TurtleBot4/` |

## Structure

- `ALOHA/` - product page, project overview page, and contact form section
- `X-Series Arms/` - landing page and product carousel, including a Shopify version
- `X-Series Arms/Carousel/Template/` - placeholder test content, not a product page
- `LoCoBots/` - landing page plus one folder per LoCoBot variant
- `TurtleBot4/` - three page versions (`TurtleBot4.html`, `TurtleBot4-2.0.html`, `TurtleBot4-3.0.html`), each with its own CSS file

## Usage

No install or build step. Open any product's `.html` file in a browser to preview it. Keep the folder structure intact, or shared styles and images may not load.

## Notes

- Each page has its own HTML and CSS files.
- Specs follow the Trossen Robotics documentation. Check it for current models and software versions.
- TurtleBot 4 is made by Clearpath Robotics, not Interbotix. -- Important!