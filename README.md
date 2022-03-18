# rethinking-challenging-ranks-visual-channels-paper

Materials for the presentation of the paper: "[Rethinking the Ranks of Visual Channels](https://arxiv.org/abs/2107.11367)" (Caitlyn M. McColeman, Fumeng Yang, Steven Franconeri, Timothy F. Brady — IEEE VIS 2021).

## References

- [Annotated paper](https://github.com/joaopalmeiro/annotated-papers/blob/main/data-visualization/rethinking_the_ranks_of_visual_channels.pdf).
- [Composable Vue](https://github.com/antfu/talks/tree/master/2021-04-29) talk by Anthony Fu.
- [An Examination of Cleveland and McGill's Hierarchy of Graphical Elements](https://www.researchgate.net/publication/221249388_An_Examination_of_Cleveland_and_McGill%27s_Hierarchy_of_Graphical_Elements) thesis by Brandie Michelle Stewart.
- [Graphical perception — learn the fundamentals first](https://flowingdata.com/2010/03/20/graphical-perception-learn-the-fundamentals-first/) blog post by FlowingData.
- [Tweet](https://twitter.com/fumeng_yang/status/1451635789016805377) by Fumeng Yang.

## Development

- `pnpm install`.
- `pnpm dev`.

## Notes

- `pnpm install @slidev/cli @slidev/theme-default`.
- `convert public/2107.11367_page1.png -geometry x1920 public/2107.11367_page1_1920.png`.
- [1440 × 900 (WXGA+, WSXGA)](<https://en.wikipedia.org/wiki/Graphics_display_resolution#WXGA+_(1440%C3%97900)>). 16:10.
- [Figma](https://www.figma.com/file/OpherFzBmFElT3dWEAibng/rankings?node-id=0%3A1).
- Prettier:
  - [Extract shebang and front matter to be part of the plugin api](https://github.com/prettier/prettier/issues/4774) (open) issue.
  - [prettier-plugin-pkg](https://github.com/rx-ts/prettier/tree/master/packages/pkg) (`package.json`).
  - [prettier-plugin-sh](https://github.com/rx-ts/prettier/tree/master/packages/sh).
- [Minimal Slide Deck Template](https://www.figma.com/community/file/969103389041074315).
