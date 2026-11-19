# Project memory

## Product intent & audience

- Excalidraw-based whiteboard/drawing app.
- Users can draw shapes, add text, collaborate on shared boards, and export drawings.
- No accounts or database required — client-side only.

## Brand personality & voice

- Hand-drawn, informal, creative-tool aesthetic inherited from Excalidraw.
- Guidance tone: direct, friendly, feature-oriented.

## Visual design & UX direction

- Built on Excalidraw component library; hand-drawn visual style.
- Welcome screen, toolbar, menus, and canvas are core UI surfaces.
- Customizable entry points: welcome screen, colors, menus.
- Responsive preview; primary interactions are canvas drawing, text, shape tools, export.

## Decisions, constraints & rationale

- Framework: Vite + React.
- Dependencies were pre-installed; no additional setup needed.
- Production build verified and passes; only warnings are large bundle size and outdated browser data — non-blocking.
- No backend/database/auth — app is fully client-side.

## Open questions & assumptions

- Specific customization goals (welcome screen, colors, menus) not yet defined.
- Collaboration implementation assumed handled within Excalidraw defaults; no custom backend confirmed.
- Export format(s) and further feature additions not specified.