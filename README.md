Staking Mechanics

Users can stake their HFV tokens to earn fixed APY rewards calculated using a transparent and on-chain formula.

Staking Formula:

Reward = Staked HFV × 0.4 × 17.38

This equates to approximately 695% APY

Minimum staking lock period: 21 days

Claiming Rewards:

Rewards are paid from the MF (Managed Fund)

If MF lacks enough HFV to pay the full reward, the contract will automatically pull the missing amount from PSF, ensuring smooth payout

PSF must pre-approve the staking contract to allow this transfer

6. PSF & MF Logic

PSF is a reserve fund to support the MF when it becomes underfunded

MF is the operational fund from which all staking rewards are paid

PSF Access Control:

The owner may access or withdraw from PSF only if MF cannot sustain payouts

This ensures transparency and sustainability while protecting against fund exhaustion
