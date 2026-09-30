<h1 align="center">Davis Reyes</h1>
<h3 align="center">Independent contractor. Solana &amp; EVM. I build, review, and ship.</h3>

---

**Build** - protocols, tooling, SDKs, bots. Rust/Anchor, Solidity/Foundry, TypeScript.

**Review** - contracts, SDKs, and the services around them. Findings land as issues
and running PoCs, not PDFs.

**Fix** - I don't just report bugs. My PRs come with the patch and the regression test.

## Public work

| Date | Project | Scope | Link |
|---|---|---|---|
| Sep 2026 | Loopscale | Pricing adapter: rounding floor would zero LP redemptions under par; suggested fix adopted by maintainer | [loopscale-pricing-adapters#3](https://github.com/LoopscaleLabs/loopscale-pricing-adapters/issues/3) |
| Sep 2026 | GMX Solana | Builder-fee JS SDK review: stale-hint liveness trap on settle/close | [gmx-solana#447](https://github.com/gmsol-labs/gmx-solana/pull/447) |
| Sep 2026 | GMX Solana | Caught a reintroduced shared `final_output_token` bug in the builder-fee API | [gmx-solana#445](https://github.com/gmsol-labs/gmx-solana/pull/445) |
| Sep 2026 | GMX Solana | Liquidation-price fix review, verified against the on-chain path | [gmx-solana#439](https://github.com/gmsol-labs/gmx-solana/pull/439) |
| Sep 2026 | Hylo | Token-2022 collateral extension policy, incl. on-chain readout | [hylo-so/sdk#135](https://github.com/hylo-so/sdk/issues/135) |
| Sep 2026 | Hylo | Off-hours pricing design for equity-backed xAssets | [hylo-so/sdk#136](https://github.com/hylo-so/sdk/issues/136) |
| Aug 2026 | GMX Solana | Builder-fee routing bug found on read-through; wrote fix + regression test | [#416](https://github.com/gmsol-labs/gmx-solana/pull/416) |
| Aug 2026 | GMX Solana | 0.10.0 npm package shipped empty (381-byte tarball) | [gmx-solana#417](https://github.com/gmsol-labs/gmx-solana/issues/417) |
| Aug 2026 | AlphaLend | Zero-LTV collateral seizable in live liquidations | [alphalend#18](https://github.com/AlphaFiTech/alphalend-contracts-interfaces/issues/18) |

## Tools

- [sol-pr-guard](https://github.com/mv-reyes/sol-pr-guard) - diff-scoped security review for Solana PRs

## Contact

GitHub issues, or the email in my commits. Small, well-defined scope to start:
one program, one flow, one question.
