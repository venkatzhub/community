# Development Checkpoint

Introduction
------------
To provide overall project status and to have a place to identify all critical issues and identify action, owners and review timelines.

Schedule
--------

Current
- Zowe 1.11.0 (March 31, 2020 - April 28, 2020)
-  **PLEASE ASK YOUR TEAM TO VERIFY THE MINOR VERSION LEVEL OF YOUR COMPONENT DEFINED IN [manifest.json.template binaryDependencies](https://github.com/zowe/zowe-install-packaging/blob/staging/manifest.json.template#L13).**
- Sprint 1 (March 31, 2020 - April 13, 2020)
- Sprint 2 (April 14, 2020 - April 27, 2020)
- Code Complete/RC Candidate Build (April 24, 2020)
   - **PLEASE NOTIFY CI/CD SQUAD FOR THE VERSIONS YOU WANT TO RELEASE, OR CREATE PR AGAINST RC BRANCH.**
- System Demo (April 27, 2020)
- 1.11.0 GA (April 28 2020)

Next
Zowe 1.12.0 (April 28, 2020 - May 26, 2020)
- Sprint 1 (April 28, 2020 - May 11, 2020)
- Sprint 2 (May 12, 2020 - May 25, 2020)
- Code Complete/RC Candidate Build (May 22, 2020)
- System Demo (May 25, 2020)
- 1.12.0 GA (May 26, 2020)

Agenda Items
------------
1. Start Recording
2. ZLC Updates
3. Current Release and Build Status (Jack/Mark)
   - There are several failures in the nightly builds of this week, currently the nightly build is not green.
     - We don't have new PTF number in ptf-bucket.txt after v1.10.0 released. - This has been resolved.
     - There were several failures were caused by network or server lag. - The issue requires more investigation and we may need help from the developers who working on workflow.
     - The smoke tests failed on login to Desktop. - Solution is pending.
4. Plan
     - Discuss 1.11.0 Release
     - Discuss Joint PI Planning
     - RC Process Improvements
5. Squad Status:
    - Onboarding (JoeW/Taylor/Rose)
    - Core/Web/Editor (JPL/Nolan/James)
      - Implemented new login screen with passsword reset UI
      - Embed desktop styling changes via personalization panel
    - API Mediation Layer & Security (Elliot/Michal S/Petr P)
    - Foundation (CI/CD) (Mark/Jack/Nick)
      - Finished one new installation test bundle (multiple node.js versions).
      - Work on testing automating ACF2/TS test bundle.
    - Documentation (Brandon/Ashley/Jim/Jason)

6. Legal Requirements
    - None

7. Community Backlog
    - TBD
8. Roundtable
    - None

Action Items
------------
- None
