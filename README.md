# 🚀 Release Notes - Shift Simulator

### [v3.6.5] - 2026-01-20
**Final Stable Milestone**
- **Added**: Auto-formatting for messaging. Implemented "Last Two Names" logic to strip family names for a more friendly/casual tone (e.g., "John Doe" becomes "Doe").
- **Improved**: Polished the LINE message template to match the user's specific request for a professional yet approachable swap invitation.
- **Fixed**: Guaranteed strict preservation of all core logic (rest-time checks, color protection) across updates.

### [v3.6.4] - 2026-01-20
**Connectivity Update**
- **Added**: Integrated **Web Share API** & **LINE URL Scheme** bridge.
- **Added**: A "💬 Notify" button in the Modification Summary for instant coordination.
- **Improved**: Automatic message generation including Date, Shift Type, and "From <-> To" details to eliminate manual typing.

### [v3.6.3] - 2025-11-09
**Personalization & Identity**
- **Added**: Dynamic Header title. The "Modification Summary" now automatically incorporates the user's real name based on the Employee ID entered.
- **Improved**: Enhanced UI stability for mobile and desktop switching.

### [v3.6.2] - 2025-11-09
**The Efficiency Update**
- **Added**: **Batch Modification Panel**. Users can now select multiple days and swap them with a single colleague in one click.
- **Improved**: Expanded the "Shift Selection" filter, allowing users to find colleagues by specific shift prefixes (e.g., showing all "E" shifts).
- **Improved**: Modification Summary logic to group all changes by colleague for better clarity.

### [v3.6.1] - 2025-07-07
**Core Guardrails & Logic**
- **Added**: **Rest-Time Check (11-hour Rule)**. The system now automatically flags illegal swaps that violate minimum rest requirements between shifts.
- **Added**: **Role Protection**. Implemented color-based filtering (e.g., Yellow/Blue tags) to prevent swapping between different job roles (e.g., Ground vs. Flight crew).
- **Added**: Collapsible lists for non-perfect matches to reduce visual clutter on mobile devices.

### [v3.6.0] - 2025-04-22
**Initial Interactive Build**
- **Added**: Excel (`.xlsx`) parsing engine using `ExcelJS`.
- **Added**: Interactive Calendar UI with "Perfect Match" (✨) highlighting.
- **Added**: Real-time modification logs and shift swap simulation.
- **Added**: Basic Mobile/PC responsive layout toggle.
