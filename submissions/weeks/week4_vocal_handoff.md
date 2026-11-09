HANDOFF
turns: 15
learns by: example-in-context
domain: statistical inference | level: 3 | milestone: 3 reached | anchor: metric gaming
ablation | claim: no | prior: none | end: deployed | "basically ablation is changing one specific parameter to see how the model improves in terms of NLL"
model selection | claim: no | prior: none | end: deployed | "based on the best ablation performances you can try some combination of those optimizations and try out different combinations to pick the best one which is model selection"
overfitting | claim: no | prior: none | end: deployed | "we don't want too many knobs because of overfitting and want the generalized model"
generalization | claim: no | prior: none | end: deployed | "to verify whether the winning model generalizes one can simply test it on the locked data sets at the very end"
leaderboard | claim: no | prior: none | end: deployed | "to verify whether the winning model generalizes one can simply test it on the locked data sets at the very end"
metric gaming | claim: no | prior: none | end: introduced | "i don't understand we aren't supposed to do metric gaming right"
protocol fingerprint | claim: no | prior: none | end: introduced | "i dont understand metric gaming or protocol fingerprinting"
sub-additive gains | claim: no | prior: none | end: deployed | "it should definetely be smaller than the sum of the individual parts. its not like the model will have linear gains"
other deployed: paired difference, leave-one-cycle-out cross-validation, held-out log-likelihood, negative log-likelihood
other open: metric gaming, protocol fingerprint

HANDOFF
turns: 15
learns by: example-in-context
domain: solar cycle physics | level: 3 | milestone: 3 reached | anchor: hemispheric asymmetry
hemispheric asymmetry | claim: no | prior: none | end: deployed | "pooling across hemicycles i dont really understand but may have some effect"
belt width dynamics | claim: no | prior: none | end: deployed | "perhaps option A making a skewed profile for the belt width. i could see how it would have an asymmetric tail instead of being a gaussian"
buoyancy threshold | claim: no | prior: correct | end: deployed | "i would not change the bouyancy threshold emission it doesn't appear to need optimization"
other deployed: active belt skew, toroidal field
other open: hemispheric asymmetry

HANDOFF
turns: 15
learns by: example-in-context
domain: point processes | level: 3 | milestone: 3 reached | anchor: marginal intensity
marginal intensity | claim: no | prior: none | end: deployed | "because you integrate the intensity to get a marginal intensity for the KS statistic depending only on time it would make sense that changing the profile wouldnt change the KS statstic"
thinning | claim: no | prior: correct | end: deployed | "simulated butterfly diagram using thinning"
intensity surface | claim: no | prior: none | end: deployed | "the orange dashed line matches the symmetric line perfectly"
other deployed: Kolmogorov–Smirnov statistic, 2D log-likelihood, compensator
other open: none
