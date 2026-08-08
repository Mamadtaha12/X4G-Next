---
version: alpha
name: "X4G Next - VPN Gateway Panel"
description: "Modern VPN Gateway Panel with VLESS/XHTTP support, Telegram Bot integration, and Subscription Groups. Dark-futuristic aesthetic with cyan/amber accents."
colors:
  # Core Brand Colors
  primary: "#00D4AA"           # Cyan-teal accent - main brand color
  primary-hover: "#00E8BB"     # Lighter cyan for hover states
  primary-muted: "#00D4AA1A"   # 10% opacity for backgrounds
  
  secondary: "#FFB800"         # Amber/gold - warning, premium, highlights
  secondary-hover: "#FFCC33"   # Lighter amber for hover
  secondary-muted: "#FFB8001A" # 10% opacity
  
  # Semantic Colors
  success: "#00D4AA"           # Same as primary
  warning: "#FFB800"           # Same as secondary
  danger: "#FF4757"            # Red for destructive actions
  danger-hover: "#FF6B7A"
  info: "#54A0FF"              # Blue for informational
  
  # Neutral/Dark Theme Base
  background: "#0A0E14"        # Deep navy-black - main background
  surface: "#11171F"           # Card/surface background
  surface-elevated: "#181F2A"  # Elevated surfaces (modals, dropdowns)
  surface-hover: "#1E2734"     # Hover state for surfaces
  border: "#1E2A3A"            # Subtle borders
  border-strong: "#2A3A4F"     # Stronger borders for focus
  
  # Text Colors
  text-primary: "#E8F0F8"      # Primary text - near white with blue tint
  text-secondary: "#8BA4B8"    # Secondary text - muted
  text-muted: "#5A6E7E"        # Placeholder/disabled text
  text-inverse: "#0A0E14"      # Text on colored backgrounds
  text-accent: "#00D4AA"       # Accent text (links, highlights)
  text-warning: "#FFB800"      # Warning text
  
  # Status Colors (for traffic, connections, etc.)
  status-online: "#00D4AA"
  status-offline: "#6B7280"
  status-warning: "#FFB800"
  status-error: "#FF4757"
  status-limited: "#54A0FF"

typography:
  font-family-base: "JetBrains Mono, 'Fira Code', ui-monospace, SFMono-Regular, Menlo, Consolas, monospace"
  font-family-ui: "'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif"
  font-family-display: "'Space Grotesk', 'Inter', -apple-system, sans-serif"
  
  # Display / Headlines
  display-xl:
    fontFamily: "{typography.font-family-display}"
    fontSize: "clamp(2.5rem, 5vw, 4rem)"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "-0.03em"
  display-lg:
    fontFamily: "{typography.font-family-display}"
    fontSize: "clamp(2rem, 4vw, 3rem)"
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: "-0.02em"
  display-md:
    fontFamily: "{typography.font-family-display}"
    fontSize: "clamp(1.5rem, 3vw, 2.25rem)"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "-0.01em"
  display-sm:
    fontFamily: "{typography.font-family-display}"
    fontSize: "clamp(1.25rem, 2.5vw, 1.75rem)"
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: "-0.01em"
  
  # Headings
  h1:
    fontFamily: "{typography.font-family-display}"
    fontSize: "1.875rem"
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: "-0.02em"
  h2:
    fontFamily: "{typography.font-family-display}"
    fontSize: "1.5rem"
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: "-0.01em"
  h3:
    fontFamily: "{typography.font-family-display}"
    fontSize: "1.25rem"
    fontWeight: 600
    lineHeight: 1.35
  h4:
    fontFamily: "{typography.font-family-ui}"
    fontSize: "1.125rem"
    fontWeight: 600
    lineHeight: 1.4
  
  # Body Text
  body-lg:
    fontFamily: "{typography.font-family-ui}"
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.6
  body-md:
    fontFamily: "{typography.font-family-ui}"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.6
  body-sm:
    fontFamily: "{typography.font-family-ui}"
    fontSize: "0.875rem"
    fontWeight: 400
    lineHeight: 1.55
  body-xs:
    fontFamily: "{typography.font-family-ui}"
    fontSize: "0.75rem"
    fontWeight: 400
    lineHeight: 1.5
  
  # Monospace / Code / Technical
  mono-lg:
    fontFamily: "{typography.font-family-base}"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.6
    fontFeatureSettings: "'liga' 1, 'calt' 1"
  mono-md:
    fontFamily: "{typography.font-family-base}"
    fontSize: "0.875rem"
    fontWeight: 400
    lineHeight: 1.55
  mono-sm:
    fontFamily: "{typography.font-family-base}"
    fontSize: "0.75rem"
    fontWeight: 400
    lineHeight: 1.5
  
  # Labels / UI
  label-lg:
    fontFamily: "{typography.font-family-ui}"
    fontSize: "0.875rem"
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: "0.02em"
    textTransform: "uppercase"
  label-md:
    fontFamily: "{typography.font-family-ui}"
    fontSize: "0.75rem"
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: "0.03em"
    textTransform: "uppercase"
  label-sm:
    fontFamily: "{typography.font-family-ui}"
    fontSize: "0.6875rem"
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: "0.04em"
    textTransform: "uppercase"

spacing:
  # Base unit: 4px
  0: "0"
  1: "0.25rem"   # 4px
  2: "0.5rem"    # 8px
  3: "0.75rem"   # 12px
  4: "1rem"      # 16px
  5: "1.25rem"   # 20px
  6: "1.5rem"    # 24px
  8: "2rem"      # 32px
  10: "2.5rem"   # 40px
  12: "3rem"     # 48px
  16: "4rem"     # 64px
  20: "5rem"     # 80px
  24: "6rem"     # 96px

rounded:
  none: "0"
  sm: "0.375rem"   # 6px
  md: "0.5rem"     # 8px
  lg: "0.75rem"    # 12px
  xl: "1rem"       # 16px
  2xl: "1.5rem"    # 24px
  full: "9999px"

shadows:
  sm: "0 1px 2px 0 rgb(0 0 0 / 0.3)"
  md: "0 4px 6px -1px rgb(0 0 0 / 0.4), 0 2px 4px -2px rgb(0 0 0 / 0.3)"
  lg: "0 10px 15px -3px rgb(0 0 0 / 0.4), 0 4px 6px -4px rgb(0 0 0 / 0.3)"
  xl: "0 20px 25px -5px rgb(0 0 0 / 0.4), 0 8px 10px -6px rgb(0 0 0 / 0.3)"
  glow-primary: "0 0 20px rgb(0 212 170 / 0.3), 0 0 40px rgb(0 212 170 / 0.15)"
  glow-secondary: "0 0 20px rgb(255 184 0 / 0.3), 0 0 40px rgb(255 184 0 / 0.15)"
  inner: "inset 0 2px 4px 0 rgb(0 0 0 / 0.4)"

elevation:
  level-0: "none"
  level-1: "{shadows.sm}"
  level-2: "{shadows.md}"
  level-3: "{shadows.lg}"
  level-4: "{shadows.xl}"

border-width:
  thin: "1px"
  medium: "2px"
  thick: "3px"

transitions:
  fast: "150ms cubic-bezier(0.4, 0, 0.2, 1)"
  normal: "200ms cubic-bezier(0.4, 0, 0.2, 1)"
  slow: "300ms cubic-bezier(0.4, 0, 0.2, 1)"

z-index:
  dropdown: 100
  sticky: 200
  modal-backdrop: 300
  modal: 400
  popover: 500
  tooltip: 600
  toast: 700

components:
  # ========== BUTTONS ==========
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.text-inverse}"
    fontFamily: "{typography.font-family-ui}"
    fontSize: "{typography.body-sm.fontSize}"
    fontWeight: 600
    padding: "0.625rem 1.25rem"
    rounded: "{rounded.md}"
    border: "none"
    cursor: "pointer"
    transition: "all {transitions.fast}"
    boxShadow: "{shadows.glow-primary}"
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
    boxShadow: "0 0 30px rgb(0 212 170 / 0.4), 0 0 60px rgb(0 212 170 / 0.2)"
    transform: "translateY(-1px)"
  button-primary-active:
    backgroundColor: "#00B894"
    transform: "translateY(0)"
    boxShadow: "{shadows.glow-primary}"
  button-primary-disabled:
    backgroundColor: "#00D4AA40"
    cursor: "not-allowed"
    boxShadow: "none"
    opacity: 0.5
  
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.primary}"
    fontFamily: "{typography.font-family-ui}"
    fontSize: "{typography.body-sm.fontSize}"
    fontWeight: 600
    padding: "0.625rem 1.25rem"
    rounded: "{rounded.md}"
    border: "1px solid {colors.primary}"
    cursor: "pointer"
    transition: "all {transitions.fast}"
  button-secondary-hover:
    backgroundColor: "{colors.primary-muted}"
    boxShadow: "{shadows.glow-primary}"
  button-secondary-active:
    backgroundColor: "{colors.primary-muted}"
  
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.text-secondary}"
    fontFamily: "{typography.font-family-ui}"
    fontSize: "{typography.body-sm.fontSize}"
    fontWeight: 500
    padding: "0.5rem 1rem"
    rounded: "{rounded.md}"
    border: "none"
    cursor: "pointer"
    transition: "all {transitions.fast}"
  button-ghost-hover:
    backgroundColor: "{colors.surface-hover}"
    textColor: "{colors.text-primary}"
  
  button-danger:
    backgroundColor: "{colors.danger}"
    textColor: "{colors.text-inverse}"
    fontFamily: "{typography.font-family-ui}"
    fontSize: "{typography.body-sm.fontSize}"
    fontWeight: 600
    padding: "0.625rem 1.25rem"
    rounded: "{rounded.md}"
    border: "none"
    cursor: "pointer"
    transition: "all {transitions.fast}"
  button-danger-hover:
    backgroundColor: "{colors.danger-hover}"
    boxShadow: "0 0 20px rgb(255 71 87 / 0.4)"
  
  button-icon:
    backgroundColor: "transparent"
    textColor: "{colors.text-secondary}"
    padding: "0.5rem"
    rounded: "{rounded.md}"
    border: "none"
    cursor: "pointer"
    transition: "all {transitions.fast}"
    display: "flex"
    alignItems: "center"
    justifyContent: "center"
  button-icon-hover:
    backgroundColor: "{colors.surface-hover}"
    textColor: "{colors.text-primary}"

  # ========== INPUTS ==========
  input-base:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text-primary}"
    placeholderColor: "{colors.text-muted}"
    fontFamily: "{typography.font-family-ui}"
    fontSize: "{typography.body-md.fontSize}"
    fontWeight: 400
    padding: "0.625rem 0.875rem"
    rounded: "{rounded.md}"
    border: "1px solid {colors.border}"
    transition: "all {transitions.fast}"
    width: "100%"
  input-focus:
    borderColor: "{colors.primary}"
    boxShadow: "0 0 0 3px {colors.primary-muted}"
    outline: "none"
  input-error:
    borderColor: "{colors.danger}"
  input-error-focus:
    boxShadow: "0 0 0 3px rgb(255 71 87 / 0.15)"
  input-disabled:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text-muted}"
    cursor: "not-allowed"
    opacity: 0.6
  
  input-label:
    fontFamily: "{typography.font-family-ui}"
    fontSize: "{typography.label-sm.fontSize}"
    fontWeight: 600
    color: "{colors.text-secondary}"
    marginBottom: "0.375rem"
    display: "block"
  
  input-helper:
    fontFamily: "{typography.font-family-ui}"
    fontSize: "{typography.body-xs.fontSize}"
    color: "{colors.text-muted}"
    marginTop: "0.375rem"
  
  input-error-text:
    fontFamily: "{typography.font-family-ui}"
    fontSize: "{typography.body-xs.fontSize}"
    color: "{colors.danger}"
    marginTop: "0.375rem"

  # ========== SELECT / DROPDOWN ==========
  select-base:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text-primary}"
    fontFamily: "{typography.font-family-ui}"
    fontSize: "{typography.body-md.fontSize}"
    padding: "0.625rem 2.5rem 0.625rem 0.875rem"
    rounded: "{rounded.md}"
    border: "1px solid {colors.border}"
    cursor: "pointer"
    transition: "all {transitions.fast}"
    appearance: "none"
    backgroundImage: "url(\"data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 24 24' fill='none' stroke='%238BA4B8' stroke-width='2' stroke-linecap='round' stroke-linejoin='round'%3E%3Cpolyline points='6 9 12 15 18 9'%3E%3C/polyline%3E%3C/svg%3E\")"
    backgroundRepeat: "no-repeat"
    backgroundPosition: "right 0.75rem center"
    paddingRight: "2.5rem"
  select-focus:
    borderColor: "{colors.primary}"
    boxShadow: "0 0 0 3px {colors.primary-muted}"
    outline: "none"

  # ========== CARDS ==========
  card-base:
    backgroundColor: "{colors.surface}"
    border: "1px solid {colors.border}"
    rounded: "{rounded.lg}"
    padding: "{spacing.6}"
    transition: "all {transitions.normal}"
  card-hover:
    borderColor: "{colors.border-strong}"
    boxShadow: "{shadows.lg}"
    transform: "translateY(-2px)"
  card-glass:
    backgroundColor: "rgba(17, 23, 31, 0.8)"
    backdropFilter: "blur(12px)"
    border: "1px solid {colors.border}"
    rounded: "{rounded.lg}"
    padding: "{spacing.6}"
  
  card-header:
    padding: "{spacing.4} {spacing.5}"
    borderBottom: "1px solid {colors.border}"
  card-body:
    padding: "{spacing.5}"
  card-footer:
    padding: "{spacing.4} {spacing.5}"
    borderTop: "1px solid {colors.border}"
    backgroundColor: "{colors.surface}"

  # ========== TABLE ==========
  table-container:
    overflowX: "auto"
    rounded: "{rounded.lg}"
    border: "1px solid {colors.border}"
    backgroundColor: "{colors.surface}"
  table-base:
    width: "100%"
    borderCollapse: "collapse"
    fontFamily: "{typography.font-family-ui}"
    fontSize: "{typography.body-sm.fontSize}"
  table-header:
    backgroundColor: "{colors.surface}"
    borderBottom: "1px solid {colors.border}"
  table-header-cell:
    textColor: "{colors.text-secondary}"
    fontFamily: "{typography.font-family-ui}"
    fontSize: "{typography.label-sm.fontSize}"
    fontWeight: 600
    textAlign: "left"
    padding: "{spacing.3} {spacing.4}"
    textTransform: "uppercase"
    letterSpacing: "0.03em"
  table-body:
    backgroundColor: "{colors.background}"
  table-row:
    borderBottom: "1px solid {colors.border}"
    transition: "background-color {transitions.fast}"
  table-row-hover:
    backgroundColor: "{colors.surface-hover}"
  table-cell:
    textColor: "{colors.text-primary}"
    padding: "{spacing.3} {spacing.4}"
    fontFamily: "{typography.mono-md.fontFamily}"
    fontSize: "{typography.mono-sm.fontSize}"
  table-cell-text:
    textColor: "{colors.text-primary}"
    fontFamily: "{typography.font-family-ui}"
    fontSize: "{typography.body-sm.fontSize}"

  # ========== BADGES / STATUS ==========
  badge-base:
    fontFamily: "{typography.font-family-ui}"
    fontSize: "{typography.label-sm.fontSize}"
    fontWeight: 600
    padding: "0.125rem 0.5rem"
    rounded: "{rounded.full}"
    display: "inline-flex"
    alignItems: "center"
    gap: "0.25rem"
  badge-online:
    backgroundColor: "{colors.status-online}"
    color: "{colors.text-inverse}"
  badge-offline:
    backgroundColor: "{colors.status-offline}"
    color: "{colors.text-inverse}"
  badge-warning:
    backgroundColor: "{colors.status-warning}"
    color: "{colors.text-inverse}"
  badge-error:
    backgroundColor: "{colors.status-error}"
    color: "{colors.text-inverse}"
  badge-limited:
    backgroundColor: "{colors.status-limited}"
    color: "{colors.text-inverse}"
  badge-premium:
    backgroundColor: "{colors.secondary}"
    color: "{colors.text-inverse}"
    animation: "pulse-gold 2s ease-in-out infinite"

  # ========== TABS ==========
  tabs-container:
    display: "flex"
    gap: "{spacing.1}"
    backgroundColor: "{colors.surface}"
    padding: "{spacing.1}"
    rounded: "{rounded.lg}"
    border: "1px solid {colors.border}"
  tab-base:
    fontFamily: "{typography.font-family-ui}"
    fontSize: "{typography.body-sm.fontSize}"
    fontWeight: 500
    color: "{colors.text-secondary}"
    padding: "{spacing.2} {spacing.4}"
    rounded: "{rounded.md}"
    border: "none"
    backgroundColor: "transparent"
    cursor: "pointer"
    transition: "all {transitions.fast}"
  tab-active:
    color: "{colors.text-inverse}"
    backgroundColor: "{colors.primary}"
    boxShadow: "{shadows.glow-primary}"
  tab-hover:
    color: "{colors.text-primary}"
    backgroundColor: "{colors.surface-hover}"

  # ========== SIDEBAR / NAV ==========
  sidebar-base:
    backgroundColor: "{colors.surface}"
    borderRight: "1px solid {colors.border}"
    width: "16rem"
    height: "100vh"
    display: "flex"
    flexDirection: "column"
  sidebar-item:
    fontFamily: "{typography.font-family-ui}"
    fontSize: "{typography.body-sm.fontSize}"
    fontWeight: 500
    color: "{colors.text-secondary}"
    padding: "{spacing.3} {spacing.4}"
    rounded: "{rounded.md}"
    margin: "{spacing.1} {spacing.3}"
    display: "flex"
    alignItems: "center"
    gap: "{spacing.3}"
    transition: "all {transitions.fast}"
    cursor: "pointer"
    border: "none"
    backgroundColor: "transparent"
    width: "100%"
    textAlign: "left"
  sidebar-item-hover:
    color: "{colors.text-primary}"
    backgroundColor: "{colors.surface-hover}"
  sidebar-item-active:
    color: "{colors.text-inverse}"
    backgroundColor: "{colors.primary}"
    boxShadow: "{shadows.glow-primary}"

  # ========== MODAL ==========
  modal-overlay:
    backgroundColor: "rgba(10, 14, 20, 0.8)"
    backdropFilter: "blur(4px)"
    position: "fixed"
    inset: 0
    zIndex: "{z-index.modal-backdrop}"
  modal-base:
    backgroundColor: "{colors.surface-elevated}"
    border: "1px solid {colors.border}"
    rounded: "{rounded.xl}"
    boxShadow: "{shadows.xl}"
    maxWidth: "32rem"
    width: "90%"
    maxHeight: "90vh"
    overflow: "auto"
    zIndex: "{z-index.modal}"
  modal-header:
    padding: "{spacing.5} {spacing.6}"
    borderBottom: "1px solid {colors.border}"
    display: "flex"
    alignItems: "center"
    justifyContent: "space-between"
  modal-title:
    fontFamily: "{typography.font-family-display}"
    fontSize: "{typography.h3.fontSize}"
    fontWeight: 600
    color: "{colors.text-primary}"
  modal-close:
    backgroundColor: "transparent"
    border: "none"
    color: "{colors.text-muted}"
    cursor: "pointer"
    padding: "{spacing.2}"
    rounded: "{rounded.md}"
    transition: "all {transitions.fast}"
  modal-close-hover:
    color: "{colors.text-primary}"
    backgroundColor: "{colors.surface-hover}"
  modal-body:
    padding: "{spacing.6}"
  modal-footer:
    padding: "{spacing.4} {spacing.6}"
    borderTop: "1px solid {colors.border}"
    display: "flex"
    justifyContent: "flex-end"
    gap: "{spacing.3}"

  # ========== TOAST / NOTIFICATION ==========
  toast-base:
    backgroundColor: "{colors.surface-elevated}"
    border: "1px solid {colors.border}"
    rounded: "{rounded.lg}"
    padding: "{spacing.4} {spacing.5}"
    boxShadow: "{shadows.xl}"
    display: "flex"
    alignItems: "flex-start"
    gap: "{spacing.3}"
    minWidth: "20rem"
    maxWidth: "28rem"
    animation: "slide-in 0.3s ease-out"
  toast-success:
    borderLeft: "4px solid {colors.success}"
  toast-warning:
    borderLeft: "4px solid {colors.warning}"
  toast-error:
    borderLeft: "4px solid {colors.danger}"
  toast-info:
    borderLeft: "4px solid {colors.info}"

  # ========== LOADING / SKELETON ==========
  skeleton-base:
    background: "linear-gradient(90deg, {colors.surface} 25%, {colors.surface-hover} 50%, {colors.surface} 75%)"
    backgroundSize: "200% 100%"
    animation: "shimmer 1.5s infinite"
    rounded: "{rounded.md}"
  skeleton-text:
    height: "1rem"
    width: "100%"
  skeleton-circle:
    borderRadius: "50%"
  skeleton-rect:
    borderRadius: "{rounded.md}"

  # ========== QR CODE / TECHNICAL DISPLAY ==========
  code-block:
    backgroundColor: "{colors.background}"
    border: "1px solid {colors.border}"
    rounded: "{rounded.md}"
    padding: "{spacing.4}"
    fontFamily: "{typography.font-family-base}"
    fontSize: "{typography.mono-sm.fontSize}"
    lineHeight: 1.6
    overflowX: "auto"
    color: "{colors.text-primary}"
  qr-container:
    display: "flex"
    flexDirection: "column"
    alignItems: "center"
    gap: "{spacing.4}"
    padding: "{spacing.6}"
    backgroundColor: "{colors.surface}"
    border: "1px solid {colors.border}"
    rounded: "{rounded.lg}"
  qr-image:
    backgroundColor: "white"
    padding: "{spacing.3}"
    rounded: "{rounded.md}"

  # ========== STATS / METRICS ==========
  stat-card:
    backgroundColor: "{colors.surface}"
    border: "1px solid {colors.border}"
    rounded: "{rounded.lg}"
    padding: "{spacing.5}"
    transition: "all {transitions.normal}"
  stat-card-hover:
    borderColor: "{colors.primary}"
    boxShadow: "{shadows.glow-primary}"
  stat-icon:
    width: "3rem"
    height: "3rem"
    rounded: "{rounded.lg}"
    display: "flex"
    alignItems: "center"
    justifyContent: "center"
    fontSize: "1.5rem"
  stat-icon-primary:
    backgroundColor: "{colors.primary-muted}"
    color: "{colors.primary}"
  stat-icon-warning:
    backgroundColor: "{colors.secondary-muted}"
    color: "{colors.secondary}"
  stat-icon-danger:
    backgroundColor: "rgb(255 71 87 / 0.1)"
    color: "{colors.danger}"
  stat-icon-info:
    backgroundColor: "rgb(84 160 255 / 0.1)"
    color: "{colors.info}"
  stat-value:
    fontFamily: "{typography.font-family-display}"
    fontSize: "2rem"
    fontWeight: 700
    color: "{colors.text-primary}"
    lineHeight: 1.1
  stat-label:
    fontFamily: "{typography.font-family-ui}"
    fontSize: "{typography.label-md.fontSize}"
    color: "{colors.text-secondary}"
    textTransform: "uppercase"
    letterSpacing: "0.03em"
    marginTop: "{spacing.2}"

  # ========== PROGRESS / TRAFFIC BAR ==========
  progress-base:
    height: "0.5rem"
    backgroundColor: "{colors.background}"
    rounded: "{rounded.full}"
    overflow: "hidden"
  progress-fill:
    height: "100%"
    borderRadius: "inherit"
    transition: "width {transitions.slow}"
  progress-primary:
    background: "linear-gradient(90deg, {colors.primary}, {colors.primary-hover})"
  progress-warning:
    background: "linear-gradient(90deg, {colors.secondary}, {colors.secondary-hover})"
  progress-danger:
    background: "linear-gradient(90deg, {colors.danger}, {colors.danger-hover})"
  progress-label:
    fontFamily: "{typography.mono-sm.fontFamily}"
    fontSize: "{typography.mono-xs.fontSize}"
    color: "{colors.text-secondary}"
    marginTop: "{spacing.1}"

  # ========== QR CODE PAGE / PUBLIC SUB PAGE ==========
  public-page-container:
    minHeight: "100vh"
    background: "linear-gradient(180deg, {colors.background} 0%, {colors.surface} 100%)"
    padding: "{spacing.8} {spacing.4}"
  public-page-card:
    maxWidth: "42rem"
    margin: "0 auto"
    backgroundColor: "{colors.surface}"
    border: "1px solid {colors.border}"
    rounded: "{rounded.xl}"
    overflow: "hidden"
    boxShadow: "{shadows.xl}"
  public-page-header:
    background: "linear-gradient(135deg, {colors.primary-muted} 0%, {colors.secondary-muted} 100%)"
    padding: "{spacing.8} {spacing.6}"
    textAlign: "center"
    borderBottom: "1px solid {colors.border}"
  public-page-title:
    fontFamily: "{typography.font-family-display}"
    fontSize: "{typography.display-md.fontSize}"
    fontWeight: 700
    color: "{colors.text-primary}"
    marginBottom: "{spacing.2}"
  public-page-subtitle:
    fontFamily: "{typography.font-family-ui}"
    fontSize: "{typography.body-lg.fontSize}"
    color: "{colors.text-secondary}"
  public-page-body:
    padding: "{spacing.8} {spacing.6}"
  config-list:
    display: "flex"
    flexDirection: "column"
    gap: "{spacing.3}"
  config-item:
    display: "flex"
    alignItems: "center"
    justifyContent: "space-between"
    padding: "{spacing.4} {spacing.5}"
    backgroundColor: "{colors.surface}"
    border: "1px solid {colors.border}"
    rounded: "{rounded.lg}"
    transition: "all {transitions.fast}"
  config-item-hover:
    borderColor: "{colors.primary}"
    boxShadow: "{shadows.glow-primary}"
  config-info:
    display: "flex"
    flexDirection: "column"
    gap: "{spacing.1}"
  config-name:
    fontFamily: "{typography.font-family-display}"
    fontSize: "{typography.h4.fontSize}"
    fontWeight: 600
    color: "{colors.text-primary}"
  config-meta:
    display: "flex"
    alignItems: "center"
    gap: "{spacing.3}"
    fontFamily: "{typography.font-family-ui}"
    fontSize: "{typography.body-sm.fontSize}"
    color: "{colors.text-secondary}"
  config-qr-btn:
    padding: "{spacing.2} {spacing.4}"
    backgroundColor: "transparent"
    border: "1px solid {colors.border}"
    color: "{colors.text-secondary}"
    rounded: "{rounded.md}"
    fontSize: "{typography.body-sm.fontSize}"
    fontWeight: 500
    cursor: "pointer"
    transition: "all {transitions.fast}"
  config-qr-btn-hover:
    borderColor: "{colors.primary}"
    color: "{colors.primary}"
    backgroundColor: "{colors.primary-muted}"

  # ========== LOGIN PAGE ==========
  login-container:
    minHeight: "100vh"
    display: "flex"
    alignItems: "center"
    justifyContent: "center"
    padding: "{spacing.4}"
    background: "linear-gradient(180deg, {colors.background} 0%, #0D131B 100%)"
  login-card:
    width: "100%"
    maxWidth: "28rem"
    backgroundColor: "{colors.surface}"
    border: "1px solid {colors.border}"
    rounded: "{rounded.xl}"
    padding: "{spacing.8} {spacing.6}"
    boxShadow: "{shadows.xl}"
  login-header:
    textAlign: "center"
    marginBottom: "{spacing.8}"
  login-logo:
    width: "4rem"
    height: "4rem"
    margin: "0 auto {spacing.4}"
    background: "linear-gradient(135deg, {colors.primary}, {colors.secondary})"
    rounded: "{rounded.xl}"
    display: "flex"
    alignItems: "center"
    justifyContent: "center"
    fontSize: "2rem"
  login-title:
    fontFamily: "{typography.font-family-display}"
    fontSize: "{typography.display-sm.fontSize}"
    fontWeight: 700
    color: "{colors.text-primary}"
    marginBottom: "{spacing.2}"
  login-subtitle:
    color: "{colors.text-secondary}"
    fontSize: "{typography.body-md.fontSize}"
  login-form:
    display: "flex"
    flexDirection: "column"
    gap: "{spacing.5}"
  login-input-group:
    display: "flex"
    flexDirection: "column"
    gap: "{spacing.2}"
  login-submit:
    marginTop: "{spacing.2}"
    width: "100%"
  login-footer:
    marginTop: "{spacing.6}"
    textAlign: "center"
    color: "{colors.text-muted}"
    fontSize: "{typography.body-sm.fontSize}"

animations:
  fade-in: "fadeIn 0.3s ease-out"
  fade-out: "fadeOut 0.2s ease-in"
  slide-in: "slideIn 0.3s ease-out"
  slide-out: "slideOut 0.2s ease-in"
  slide-up: "slideUp 0.3s ease-out"
  slide-down: "slideDown 0.2s ease-in"
  scale-in: "scaleIn 0.2s ease-out"
  scale-out: "scaleOut 0.15s ease-in"
  shimmer: "shimmer 1.5s infinite"
  pulse-gold: "pulseGold 2s ease-in-out infinite"
  pulse-primary: "pulsePrimary 2s ease-in-out infinite"
  spin: "spin 1s linear infinite"
  bounce: "bounce 0.5s ease-in-out"

breakpoints:
  sm: "640px"
  md: "768px"
  lg: "1024px"
  xl: "1280px"
  2xl: "1536px"

---

# Overview

**X4G Next** is a modern, dark-futuristic VPN Gateway Panel designed for VLESS/XHTTP proxy management. It combines a powerful admin dashboard, Telegram bot integration, public subscription pages with QR codes, and a login system.

## Design Philosophy

- **Dark-Futuristic**: Deep navy backgrounds with cyan/amber accents evoke a high-tech, secure feel
- **Technical Precision**: Monospace fonts for technical data, clean UI fonts for readability
- **Glow & Depth**: Subtle glows and layered elevation create hierarchy without harsh borders
- **Functional Beauty**: Every visual element serves a purpose - status colors, traffic bars, QR codes

## Colors

The palette centers on **Cyan-Teal (#00D4AA)** as the primary brand color, representing speed, technology, and trust. **Amber/Gold (#FFB800)** serves as the secondary accent for warnings, premium features, and highlights.

Dark theme base uses **#0A0E14** (deep navy-black) with layered surfaces (#11171F, #181F2A, #1E2734) for depth.

Semantic colors follow standard conventions: Success=Cyan, Warning=Amber, Danger=Red, Info=Blue.

All text colors meet WCAG AA contrast ratios against their backgrounds.

## Typography

**Display/Headlines**: Space Grotesk - geometric, technical, distinctive
**UI/Body**: Inter - clean, readable, excellent at small sizes
**Monospace/Code**: JetBrains Mono - ligatures, excellent for configs, URLs, keys

Hierarchy: Display XL/LG/MD/SM → H1-H4 → Body LG/MD/SM/XS → Mono LG/MD/SM/XS → Labels

## Layout & Spacing

4px base unit. Spacing scale: 0-24 (0-96px). 8px grid alignment.
Container max-width: 1280px (xl breakpoint). Sidebar: 16rem fixed.

## Elevation & Depth

4 elevation levels + glow effects for primary/secondary actions.
Glass morphism for modals/overlays with backdrop blur.

## Components

All components use token references for single-source-of-truth theming.
Variants as separate sibling keys (not nested) per DESIGN.md spec.

Key components: Buttons (5 variants), Inputs (with validation states), Select, Cards (3 variants), Table, Badges (6 statuses), Tabs, Sidebar, Modal, Toast, Skeletons, Code/QR blocks, Stats cards, Progress bars, Public page, Login page.

## Do's and Don'ts

**Do:**
- Use token references everywhere (`{colors.primary}`)
- Maintain 4px grid alignment
- Use monospace for all technical data (configs, IPs, UUIDs, traffic)
- Apply glow shadows only to primary actions
- Keep contrast ratios WCAG AA compliant

**Don't:**
- Nest component variants (use sibling keys: `button-primary-hover`, not `button-primary.hover`)
- Use raw hex values in components
- Mix font families arbitrarily
- Use pure black (#000) - use `#0A0E14` instead
- Forget focus states on interactive elements
- Use pure white text on colored buttons - use `text-inverse`