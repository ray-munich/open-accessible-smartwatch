# Open Accessible Smartwatch

**An open-source, privacy-first smartwatch concept designed with neurodivergent people for accessible everyday support.**

> **Project status:** Early-stage development / concept validation.  
> This repository describes the intended direction of the project. Features listed below are **planned, under investigation, or subject to prototype validation** and should not yet be understood as finished product specifications.

## Why this project exists

Most smartwatches are designed around touchscreens, frequent charging, closed ecosystems, cloud accounts, and interfaces that assume one standard way of interacting with technology.

We want to explore a different approach.

The Open Accessible Smartwatch is being developed in Munich with neurodivergent young adults and is intended for people who may benefit from technology that is:

- simple and predictable to operate,
- usable without a touchscreen,
- highly privacy-conscious,
- customizable,
- energy efficient,
- useful in everyday routines and stressful situations,
- open to community-built software.

The project is especially interested in accessibility for neurodivergent people, while also exploring variants and functions that may be useful for older adults and other people who benefit from clear reminders, physical controls, and low-friction interaction.

## Core principles

### Accessible interaction

The current concept avoids a touchscreen and instead explores:

- approximately 10 physical buttons,
- gesture recognition,
- tap detection on the arm or hand,
- vibration feedback,
- a display readable in bright daylight and darkness,
- simple and predictable interaction patterns.

### Privacy by design

The goal is to minimize unnecessary data collection and dependence on external cloud services.

Planned principles include:

- local storage by default,
- encrypted personal data,
- encrypted communication,
- no advertising-based business model,
- no requirement for a large vendor to access personal data,
- a hardware security element for sensitive keys and credentials.

The exact security architecture has not yet been finalized and will need independent review before strong security claims can be made.

### Low-power hardware

The project is exploring a highly energy-efficient design with:

- low-power display technology,
- solar charging support,
- energy-conscious software,
- long battery life depending on usage.

The goal is to reduce charging frequency substantially. Claims such as indefinite operation from solar power will only be made if they can be demonstrated under clearly defined conditions.

### Open software

The project intends to provide:

- an open API,
- open-source applications,
- documentation for developers,
- community-extensible software.

The exact hardware licensing model and the scope of open hardware documentation are still being defined.

## Planned hardware

The current design direction includes:

- heart-rate sensor,
- blood-oxygen sensor,
- multiple high-resolution motion sensors,
- Bluetooth,
- Meshtastic-compatible communication under investigation,
- vibration motor,
- hardware security element,
- solar cells,
- approximately 60 LEDs for signaling and short-duration illumination.

Possible LED uses include:

- visual alerts,
- red emergency signaling,
- Morse or other light signals,
- short-duration flashlight functionality.

## Communication

We are exploring communication between nearby watches and compatible mesh-network nodes without relying exclusively on conventional mobile infrastructure.

Possible use cases include:

- short messages between devices,
- emergency signaling,
- local communication over longer distances through mesh nodes,
- optional gateways to internet-connected services.

The exact achievable range, reliability, regulatory requirements, and power consumption still need prototype testing.

## Positioning and navigation

One research goal is to improve positioning and navigation while reducing dependence on continuous GPS use.

Planned research areas include:

- motion-sensor-based dead reckoning,
- indoor navigation,
- station and public-building navigation,
- user-saved indoor maps,
- route guidance,
- public transport information.

Accurate positioning without GPS is technically challenging and is currently a **research goal, not a finished capability**.

## Planned software ideas

Possible applications include:

### Navigation

A future navigation app may combine:

- outdoor route guidance,
- public transport departures,
- route calculation,
- stored tickets,
- indoor directions in stations and public buildings.

### Everyday support

Planned concepts include:

- reminders,
- routines,
- timers,
- hydration reminders,
- medication reminders,
- structured daily schedules.

### Communication

A future encrypted messenger is being explored for device-to-device communication.

### Health-related support

Some planned applications may support people in recognizing routines, physiological signals, or stressful situations.

These functions are not currently presented as medical diagnosis or treatment functions. Any future medical-device functionality would require separate technical, clinical, and regulatory evaluation.

## Emergency-support concept

One planned feature is a configurable emergency button for situations such as:

- severe disorientation,
- dissociation,
- seizures or seizure-like emergencies,
- other situations in which the wearer wants rapid support.

The concept is to allow a preconfigured message and location information to be shared with selected trusted contacts.

This feature is still under development. Reliability, positioning accuracy, connectivity limitations, consent, privacy, and safety behavior will need extensive testing before it can be relied upon in emergencies.

## A version for older adults

We are also exploring a simplified configuration for older users, potentially including:

- medication reminders,
- hydration reminders,
- daily routine prompts,
- simple physical controls,
- emergency-support functions.

## Affordability

The long-term target retail price is currently around **€250**, subject to engineering and manufacturing costs.

We also want to explore a social-access model so that people who genuinely benefit from the device but cannot afford it may eventually receive a device free of charge or at a strongly reduced price.

No financing model for this has been finalized yet.

## Why neurodivergent-led development matters

This project is not based on the idea that neurodivergent people need technology designed *for* them by somebody else.

We want neurodivergent people to participate directly in:

- defining requirements,
- testing interaction concepts,
- identifying overload and usability problems,
- prioritizing features,
- communicating the project,
- shaping the development culture.

The aim is technology that adapts to people rather than forcing people to adapt to the technology.

## Current stage

We are currently in the **early development and community-building phase**.

The immediate priorities are:

1. refine the minimum viable hardware concept,
2. validate critical technical assumptions,
3. define the first prototype,
4. build a small contributor community,
5. document the project clearly,
6. prepare for a future Crowd Supply application once a demonstrable prototype exists.

## We are looking for contributors

You do **not** need to be a hardware engineer to help.

Right now we especially welcome volunteer contributors with experience in:

- community building,
- English copywriting and editing,
- social media and outreach,
- press and public relations,
- short-form video,
- graphic communication,
- accessibility,
- neurodivergent user experience,
- open-source community management,
- Crowd Supply or hardware crowdfunding,
- embedded hardware and low-power design,
- security review,
- industrial design,
- manufacturing and sourcing.

Even a few hours of feedback, an introduction, or help improving one page of documentation can be valuable.

See the repository Issues for specific ways to contribute.

## What we are *not* claiming yet

To keep the project transparent:

- there is not yet a production-ready watch,
- battery-life targets still require measurement,
- solar autonomy is not yet proven,
- GPS-free positioning accuracy is not yet proven,
- emergency features are not yet validated for safety-critical use,
- health-related features are not yet medical-device functions,
- the final security architecture has not yet completed independent review,
- the estimated retail price may change.

We would rather document uncertainty now than make promises we cannot prove later.

## Crowd Supply

Crowd Supply is a long-term goal for this project because of its focus on open hardware and technical communities.

We are **not yet running a Crowd Supply campaign**.

Our current goal is to build the prototype, documentation, contributor network, and evidence needed to become ready for a future application.

## Contributing

Please see [CONTRIBUTING.md](CONTRIBUTING.md).

If you have relevant experience and want to help, open an Issue or join an existing one.

## Location

Munich, Germany.

## License

Licensing for hardware, firmware, software, and documentation is still being selected. Until explicit license files are added, please do not assume that repository content is licensed for unrestricted reuse.
