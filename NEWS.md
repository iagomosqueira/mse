# mse 2.0
 
## USER-VISIBLE CHANGES

- genArgs renamed args
- ctrl.mp renamed ctrl
- elements of ctrl.mp don't use ctrl.## anymore
- mp oem default became NULL

## BUG FIXES

- mlc.est fixed
- it wrongly passed to goFish fixed
- oem set of dataYears fixed
- mp without oem now creates one which is conform the other objects.

# mse 1.0

## USER-VISIBLE CHANGES

- metric.phcr, C.obs and C.est added to the tracking matrix
- length.est renamed to mlc.est

## BUG FIXES

- movingF hcr and phcr fied to work with FLPars

# mse 0.9

## USER-VISIBLE CHANGES

- Complete new code base.

## BUG FIXES

## UTILITIES

## DOCUMENTATION

## DEPRECATED & DEFUNCT

# mse 0.0.4

## USER-VISIBLE CHANGES

- Methods moved to FLCore: rnoise, rlnoise
