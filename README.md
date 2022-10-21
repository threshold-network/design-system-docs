![Cover](https://user-images.githubusercontent.com/57226633/196226121-eb42efc1-e247-44a7-bfbb-3b35142b5eb4.png)

# Threshold Network Web3 Design System

This library is used by our team to build products with a consistent user experience. A design system is a complete set of standards intended to manage design at scale using reusable components and patterns.

When we first were deciding how we wanted to structure a design system, we evaluated several existing options to see what could be used for a web3 product. The web3 space has several components that are unique and important to the UX of the application, e.g. transaction modals and wallet interactions. No design system fully covered these use cases, so we decided to customize our own on top of an open source Chakra library.

If you use this in your product, we ask that you link back to this repo.

For the Figma library, you can duplicate the Figma file [here](https://www.figma.com/file/zZi2fYDUjWEMPQJWAt8VWv/Threshold-DS?node-id=3436%3A24296).

## Type of Design System
Threshold's design system is an atomic design system. An **atomic design system** structures the design system using terminology from Brad Frost’s theory of atomic design. Atomic design divides a user interface into several parts: atoms, molecules, and organisms. This type of design system includes a theming section for visual attributes (colors, typography, branding, etc). 

## 🎯 Goals
* Compile important web3 components.
* Make a resource that was open source for the community.
* Document our research and thinking for these components.
* Create designs and make changes across many files for any Threshold project faster.
* Ensure that designs are consistent across many designers and engineers.

## 📓 Foundational Principles
To be the most effective, a design system should adhere to the following:
* **Consistent**. The way components are built and managed follows a predictable pattern.
* **Independent**. The design system is built as a standalone and a single source of truth.
* **Reusable**. The components are built so they can be reused in many contexts. While it seems like a simple concept, deciding the level of specificity is one of the trickiest things about modular design. The more specific something is, the less reusable it is.
* **Accessible**. It’s usable by as many people as possible, no matter how they access the web.

## Table of Contents

### 🎨 [Theming](https://github.com/threshold-network/design-system-docs/tree/main/theming)
  * [Typography](https://github.com/threshold-network/design-system-docs/blob/main/theming/typography.md)
  * [Grids & Breakpoints](https://github.com/threshold-network/design-system-docs/blob/main/theming/gridsbreakpoints.md)
  * [Logos](https://github.com/threshold-network/design-system-docs/blob/main/theming/logos.md)
  * [Colors](https://github.com/threshold-network/design-system-docs/blob/main/theming/colors.md)
  * [Icon Library](https://github.com/threshold-network/design-system-docs/blob/main/theming/iconlibrary.md)

### 🧱 [Atoms](https://github.com/threshold-network/design-system-docs/tree/main/atoms)
  * [Avatar](https://github.com/threshold-network/design-system-docs/blob/main/atoms/avatar.md)
  * [Badge](https://github.com/threshold-network/design-system-docs/blob/main/atoms/badge.md)
  * [Banner](https://github.com/threshold-network/design-system-docs/blob/main/atoms/banner.md)
  * [Box Badge](https://github.com/threshold-network/design-system-docs/blob/main/atoms/box-badge.md)
  * [Buttons](https://github.com/threshold-network/design-system-docs/blob/main/atoms/buttons.md)
  * [Card](https://github.com/threshold-network/design-system-docs/blob/main/atoms/card.md)
  * [Divider](https://github.com/threshold-network/design-system-docs/blob/main/atoms/divider.md)
  * [Inputs](https://github.com/threshold-network/design-system-docs/blob/main/atoms/inputs.md)
  * [Notification Pill](https://github.com/threshold-network/design-system-docs/blob/main/atoms/notification-pill.md)
  * [Pending](https://github.com/threshold-network/design-system-docs/blob/main/atoms/pending.md)
  * [Progress Bar](https://github.com/threshold-network/design-system-docs/blob/main/atoms/progress-bar.md)
  * [Selection](https://github.com/threshold-network/design-system-docs/blob/main/atoms/selection.md)
  * [Shadows](https://github.com/threshold-network/design-system-docs/blob/main/atoms/shadow.md)
  * [Skeleton](https://github.com/threshold-network/design-system-docs/blob/main/atoms/skeletons.md)
  * [Slider](https://github.com/threshold-network/design-system-docs/blob/main/atoms/slider.md)
  * [Steps](https://github.com/threshold-network/design-system-docs/blob/main/atoms/steps.md)
  * [Timer](https://github.com/threshold-network/design-system-docs/blob/main/atoms/timer.md)
  * [Tooltip](https://github.com/threshold-network/design-system-docs/blob/main/atoms/tooltip.md)

### 🏡 [Molecules](https://github.com/threshold-network/design-system-docs/tree/main/molecules)
  * [Alert](https://github.com/threshold-network/design-system-docs/blob/main/molecules/alerts.md)
  * [Feature Banner](https://github.com/threshold-network/design-system-docs/blob/main/molecules/feature-banner.md)
  * [Filter Tab](https://github.com/threshold-network/design-system-docs/blob/main/molecules/filter.md)
  * [Form](https://github.com/threshold-network/design-system-docs/blob/main/molecules/form.md)
  * [Inline List](https://github.com/threshold-network/design-system-docs/blob/main/molecules/inline-list.md)
  * [Photo Uploader](https://github.com/threshold-network/design-system-docs/blob/main/molecules/photo-uploader.md)
  * [Plan](https://github.com/threshold-network/design-system-docs/blob/main/molecules/plan.md)
  * [Statistics](https://github.com/threshold-network/design-system-docs/blob/main/molecules/statistics.md)
  * [Toast](https://github.com/threshold-network/design-system-docs/blob/main/molecules/toast.md)
  * [Voting](https://github.com/threshold-network/design-system-docs/blob/main/molecules/voting.md)
  
### 🏢 [Organisms](https://github.com/threshold-network/design-system-docs/tree/main/organisms)
  * [Applications](https://github.com/threshold-network/design-system-docs/blob/main/organisms/application.md)
  * [Coverage Pool](https://github.com/threshold-network/design-system-docs/blob/main/organisms/coverage-pool.md)
  * [Modals](https://github.com/threshold-network/design-system-docs/blob/main/organisms/modals.md)
  * [Navigation](https://github.com/threshold-network/design-system-docs/blob/main/organisms/navigation.md)
  * [Rewards](https://github.com/threshold-network/design-system-docs/blob/main/organisms/rewards.md)
  * [Staking](https://github.com/threshold-network/design-system-docs/blob/main/organisms/staking.md)
  * [Table](https://github.com/threshold-network/design-system-docs/blob/main/organisms/table.md)
  * [TVL](https://github.com/threshold-network/design-system-docs/blob/main/organisms/TVL.md)
  * [Upgrade](https://github.com/threshold-network/design-system-docs/blob/main/organisms/upgrade.md)
  * [Wallet](https://github.com/threshold-network/design-system-docs/blob/main/organisms/wallet.md)

  
### 🏙️ [Layouts](https://github.com/threshold-network/design-system-docs/tree/main/layouts)
  * [Page](https://github.com/threshold-network/design-system-docs/blob/main/layouts/pages.md)
