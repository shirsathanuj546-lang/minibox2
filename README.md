# Minibox — Track Buddy (Frontend Replica)

An accurate, high-fidelity frontend replica of [boxy-track-buddy.lovable.app](https://boxy-track-buddy.lovable.app/).

## 🌟 Highlights & Features Replicated

1. **Brand & Design System**:
   - Typography: **Manrope** for headings and brand titles, **DM Sans** for body and interface text.
   - Exact Color Palette: Matching deep forest teal (`#1f6b65`), soft mint (`#edf6f5`), vibrant coral accent (`#ea580c`), and clean neutral cards.
   - Original HD cafe photography directly sourced and bundled locally (`minibox-table`, `cold-coffee`, `vada-pav`, `burger`).

2. **Routes & Pages**:
   - `/`: **Home Hero** with table photograph, brand motto, "Explore the menu" CTA, and quick menu highlights.
   - `/food`: **Full Menu** with Cold Coffee (Rs. 80), Vada Pav (Rs. 20), and Burger (Rs. 60), interactive quantity controls, and the sticky floating bottom **Cart Dock**.
   - `/cart`: **Review & Checkout** with item increment/decrement, 10-digit phone verification, and order summary.
   - **Interactive Burger Loader**: Custom floating animated burger with spinning dual-colored rings and pulsing loading dots matching the original.
   - **Payment Shell**: Embedded sandbox checkout iframe shell with reload button, security padlock, and seamless fallback.
   - `/confirmation`: **Order Confirmed** with animated celebration checkmark, festive confetti burst, complete order bill, and a live **Boxy Track Buddy** status tracker.
   - `*`: Custom **404 Page**.

3. **Bonus Polish**:
   - **Interactive Box Switcher**: Click the "Delivering to Box 07" badge in the header to change your box destination anytime (Box 01 through Box 12).
   - **Persistent Cart State**: Smooth state preservation across page navigation.

---

## 🚀 How to Run

1. Navigate to the project directory:
   ```bash
   cd "C:\Users\Yash Pawar\.gemini\antigravity\scratch\boxy-track-buddy"
   ```

2. Start the Vite dev server:
   ```bash
   npm run dev
   ```

3. Open your browser at:
   ```
   http://localhost:5173
   ```

4. Build for production:
   ```bash
   npm run build
   ```
