# MGMT 316 Management Assessment Suite

**Chapman University | Argyros College of Business and Economics**  
**Course: MGMT 316 - Management in Organizations**  
**Instructor: Professor Chip Espinoza**

---

## Overview

A comprehensive suite of 22 self-assessment tools designed for undergraduate management education. Each assessment generates personalized results with tracker codes for portfolio integration, SWOT analysis data, and detailed PDF exports.

## Features

### Student Experience
- **Clear Result Displays**: Human-readable interpretations replace cryptic codes
- **Visual Feedback**: Color-coded charts, grids, and progress indicators
- **PDF Export**: Professional multi-page reports with deep behavioral profiles
- **Mobile Responsive**: Works on desktop, tablet, and mobile devices

### Assessment Tracker Integration
- **Unified Portfolio**: All 22 assessments feed into a single tracker
- **SWOT Analysis**: Automatic compilation of strengths, weaknesses, opportunities, and threats
- **Deep Profiles**: Behavioral insights including decision style, communication preferences, and blind spots
- **Progress Tracking**: Visual completion status for all assessments

---

## Assessments Included (22 Total)

### Leadership & Management
| Assessment | File | Tracker Code |
|------------|------|--------------|
| Leadership Style (Situational) | `Leadership-Style-Assessment.html` | LSA-XXXX-X |
| Management Personality | `Management-Personality.html` | MPA-XXXX-X |
| Influence Style | `Influence-Style.html` | ISA-XXXX-XX |

### Interpersonal Skills
| Assessment | File | Tracker Code |
|------------|------|--------------|
| Conflict Management (Thomas-Kilmann) | `Conflict-Management.html` | CMA-XXXX-XX |
| Communication Style | `Communication-Style-Assessment.html` | CSA-XXXX-X |
| Team Player Style | `Team-Player.html` | TPA-XXXX-X |
| Emotional Intelligence | `EQ-Assessment.html` | EIA-XX-XXX |

### Cognitive & Decision Making
| Assessment | File | Tracker Code |
|------------|------|--------------|
| Decision Making Style | `Decision-Making-Style.html` | DMS-XXXX-XX |
| Critical Thinking | `Critical-Thinking.html` | CTA-XX-XXX |
| Strategic Thinking | `Strategic-Thinking.html` | STA-XX-XXX |
| Systems Thinking | `Systems-Thinking.html` | SYS-XX-XXX |
| Learning Style (Kolb) | `Learning-Style-Assessment.html` | LRN-XX-X |

### Personal Development
| Assessment | File | Tracker Code |
|------------|------|--------------|
| Motivation Style (McClelland) | `Motivation-Style.html` | MSA-XXXX-XX |
| Grit Assessment (Duckworth) | `Grit-Assessment.html` | GRT-XX-XXX |
| Stress Management | `Stress-Management.html` | SMS-XXXX-XX |
| Values Discovery | `Values-Discovery.html` | VDA-XXX-X |

### Organizational Readiness
| Assessment | File | Tracker Code |
|------------|------|--------------|
| Change Readiness | `Change-Readiness.html` | CRA-XX-XXXX |
| Psychological Safety | `Psychological-Safety-Assessment.html` | PSA-X-XX |
| Risk Tolerance | `Risk-Tolerance.html` | RTA-XX-XXX |

### Innovation & Ethics
| Assessment | File | Tracker Code |
|------------|------|--------------|
| Business Ethics | `Business-Ethics.html` | BEA-XXXX-X |
| Entrepreneurial Orientation | `Entrepreneurial-Orientation.html` | EOA-XX-XXX |
| Innovation Mindset | `Innovation-Mindset.html` | IMA-XX-XXX |

### Central Hub
| Tool | File | Purpose |
|------|------|---------|
| Assessment Tracker | `Assessment-Tracker-MGMT316.html` | Portfolio aggregation & SWOT compilation |
| Index | `index.html` | Navigation hub for all assessments |

---

## Installation

### GitHub Pages (Recommended)
1. Fork or clone this repository
2. Enable GitHub Pages in repository settings
3. Select `main` branch and root folder
4. Access at `https://[username].github.io/[repo-name]/`

### Local Development
```bash
git clone https://github.com/[username]/MGMT316-Assessments.git
cd MGMT316-Assessments
# Open index.html in browser
```

### Direct Hosting
Upload all `.html` files to any web server. No backend required—all assessments run entirely in the browser.

---

## Usage

### For Students
1. Navigate to `index.html` or individual assessment files
2. Enter your name and complete the assessment
3. Review your results with clear explanations
4. Copy your **Tracker Code** (displayed prominently)
5. Download your PDF report
6. Enter tracker codes into `Assessment-Tracker-MGMT316.html` to build your portfolio

### For Instructors
- Assessments are self-contained HTML files with no external dependencies
- All data stays in the student's browser (privacy-compliant)
- PDF exports include Chapman University branding
- Tracker codes enable verification without accessing student data

---

## Result Display Format

Each assessment now shows results in a clear, student-friendly format:

**Before (abbreviated):**
```
For Assessment Tracker: LSA-S1S2-S
```

**After (clear interpretation):**
```
Your Result: Leadership Style: Directing (primary) + Coaching (secondary) | Strong
Tracker Code: LSA-S1S2-S
```

---

## Technical Details

### Dependencies (included via CDN)
- **jsPDF** - PDF generation
- **html2canvas** - Chart rendering for PDFs
- No build process required

### Browser Compatibility
- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

### File Structure
```
MGMT316-Assessments/
├── README.md
├── .gitignore
├── index.html                              # Navigation hub
├── Assessment-Tracker-MGMT316.html         # Portfolio tracker
├── Leadership-Style-Assessment.html
├── Conflict-Management.html
├── EQ-Assessment.html
├── Decision-Making-Style.html
├── Communication-Style-Assessment.html
├── Team-Player.html
├── Motivation-Style.html
├── Grit-Assessment.html
├── Stress-Management.html
├── Values-Discovery.html
├── Learning-Style-Assessment.html
├── Management-Personality.html
├── Influence-Style.html
├── Critical-Thinking.html
├── Strategic-Thinking.html
├── Systems-Thinking.html
├── Change-Readiness.html
├── Psychological-Safety-Assessment.html
├── Risk-Tolerance.html
├── Business-Ethics.html
├── Entrepreneurial-Orientation.html
└── Innovation-Mindset.html
```

---

## Version History

### v2.0 (February 2026)
- Added clear "Your Result" explanations replacing abbreviations
- Enhanced PDF exports with deep behavioral profiles
- SWOT analysis integration across all assessments
- Improved mobile responsiveness
- Backward compatible with existing tracker codes

### v1.0 (January 2026)
- Initial release with 22 assessments
- Assessment Tracker with code parsing
- PDF export functionality

---

## License

Educational use only. Developed for Chapman University MGMT 316 course.

## Contact

**Professor Chip Espinoza**  
Argyros College of Business and Economics  
Chapman University

---

*Built with ❤️ for management education*
