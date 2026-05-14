# Dental Clinic Website Specification

## Project Overview
- **Project Name**: SmileCare Dental Clinic
- **Type**: Single-page responsive website
- **Core Functionality**: Modern dental clinic landing page with appointment booking CTA
- **Target Users**: Patients seeking dental care services

---

## UI/UX Specification

### Color Palette
| Color | Hex Code | Usage |
|-------|----------|-------|
| Primary Teal | `#0D9488` | Buttons, accents, highlights |
| Primary Teal Dark | `#0F766E` | Button hover states |
| Secondary Teal | `#5EEAD4` | Decorative elements, badges |
| Soft Blue | `#E0F2FE` | Background accents |
| Clean White | `#FFFFFF` | Main backgrounds |
| Off-White | `#F8FAFC` | Section backgrounds |
| Dark Text | `#1E293B` | Headlines, primary text |
| Medium Text | `#475569` | Body text, descriptions |
| Light Text | `#94A3B8` | Secondary text, captions |

### Typography
- **Primary Font**: "DM Sans" (Google Fonts) - Clean, modern, medical feel
- **Secondary Font**: "Playfair Display" (Google Fonts) - For hero headline
- **Heading Sizes**:
  - H1: 56px (desktop), 36px (mobile)
  - H2: 42px (desktop), 28px (mobile)
  - H3: 24px (desktop), 20px (mobile)
- **Body Text**: 16px / 18px
- **Small Text**: 14px

### Spacing System
- Section padding: 100px vertical (desktop), 60px (mobile)
- Container max-width: 1280px
- Component gap: 24px
- Small gap: 12px

### Responsive Breakpoints
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

---

## Component Specifications

### 1. Sticky Header Navigation
**Structure**:
- Logo (text-based): "SmileCare" with tooth icon
- Navigation links (center): Home, Services, Doctors, Reviews, Contact
- Right side: Phone number (clickable) + "Book Appointment" primary button

**Styling**:
- Background: White with subtle shadow on scroll
- Height: 80px (desktop), 70px (mobile)
- Sticky position with smooth shadow transition
- Logo: Teal color, bold, 24px

**Mobile Hamburger Menu**:
- Three-line icon
- Slide-in menu from right
- Overlay background
- Close button

**Interactions**:
- Nav links: Underline animation on hover
- Phone: Subtle scale on hover
- CTA Button: Background darken on hover

---

### 2. Hero Section
**Layout**: Split layout with content on left, visual element on right

**Content (Left Side)**:
- Headline: "Your Perfect Smile Starts Here" (Playfair Display, bold)
- Subheadline: "Budget-friendly, advanced dental care for the whole family. Modern technology meets compassionate service."
- Two buttons side-by-side:
  - Primary: "Book an Appointment" (teal background, white text)
  - Secondary: "Get Directions" (outlined, teal border)

**Dynamic Element (Floating Card)**:
- Position: Bottom right of hero content area
- Background: White with soft shadow
- Border-radius: 16px
- Content: "Next Available Slot: Today at 11:00 AM"
- Doctor placeholder: Circle image placeholder (48px)
- Subtle pulse animation on text

**Visual Side**:
- Abstract dental-themed illustration or clean gradient background
- Floating teeth/icons decoration

**Styling**:
- Background: Soft gradient from off-white to soft blue
- Min-height: 90vh (with padding consideration)

---

### 3. Trust Badges Strip
**Layout**: Horizontal row, centered, equal spacing

**4 Trust Indicators**:
1. "100% Sterilized" - Shield icon
2. "Certified Specialists" - Award/badge icon
3. "4.8★ Google Rating" - Star icon
4. "0% EMI Available" - Card/finance icon

**Styling**:
- Background: White
- Padding: 24px vertical
- Border-top: 1px solid #E2E8F0
- Each badge: Icon (teal) + text (dark)
- Icon size: 32px
- Gap between items: 48px (desktop), 24px (mobile)

---

## Functionality Specification

### Mobile Navigation
- Hamburger icon toggles slide-in menu
- Menu overlay dims background
- Close button or tap outside to close
- Smooth 300ms transition

### Header Scroll Effect
- Add shadow and slight background blur when scrolled past 50px
- Smooth transition

### Floating Card Animation
- Subtle "availability" pulse effect
- Scale animation on hover

### Button Interactions
- Hover: Scale 1.02, background color change
- Active: Scale 0.98

---

## Acceptance Criteria

1. ✅ Header is sticky and collapses to hamburger on mobile (< 768px)
2. ✅ Logo displays "SmileCare" with visual tooth element
3. ✅ Navigation shows all 5 links on desktop
4. ✅ Phone number is clickable (tel: link)
5. ✅ "Book Appointment" button visible in header
6. ✅ Hero has headline "Your Perfect Smile Starts Here"
7. ✅ Hero has subheadline about budget-friendly care
8. ✅ Two buttons displayed side-by-side
9. ✅ Floating card shows "Next Available Slot: Today at 11:00 AM"
10. ✅ Floating card includes doctor placeholder image
11. ✅ Trust badges strip shows all 4 indicators
12. ✅ All icons display correctly
13. ✅ Responsive on mobile, tablet, desktop
14. ✅ Color palette matches specification
15. ✅ Smooth animations and interactions