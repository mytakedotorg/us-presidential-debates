# <img align="left" width="90px" height="90px" src="https://raw.githubusercontent.com/mytakedotorg/mtdo/staging/_imgs/logo_leaves.png"> U.S. Presidential Debates
*Reaching for [these ideals](https://github.com/mytakedotorg/mtdo/blob/staging/factset-tooling/FACTSET_PHILOSOPHY.md) by following [these steps](https://github.com/mytakedotorg/mtdo/blob/staging/factset-tooling/FACTSET_HOWTO.md).*

## Inclusion criteria
This factset contains every televised United States Presidential Debate. This factset does not currently contain any Vice Presidential Debates, although [we plan to add them in the future](https://github.com/mytakedotorg/us-presidential-debates/issues/6).

## Notes
The first Presidential Debate took place in 1960 between John Kennedy and Richard Nixon. [No one agreed to do them again until 1976](https://github.com/mytakedotorg/us-presidential-debates/issues/4), when Jimmy Carter and Gerald Ford revived the tradition. They [almost didn't happen in 1980](https://github.com/mytakedotorg/us-presidential-debates/issues/5), but eventually did, and they have continued to take place every 4 years since then, up to and including the most recent Presidential Debate in 2020 between Joe Biden and Donald Trump.

When new Presidential Debates take place, we will add them to this factset as soon as possible.

# Changelog

## [Unreleased]
* *New event*: Added Biden Trump 2 of 2, 2020-10-22 ([PR #12](https://github.com/mytakedotorg/us-presidential-debates/pull/12))
* **Changed title of published fact**: The second of three planned presidential debates was cancelled, so there were only two. Renamed `biden-trump-1-of-3` to `biden-trump-1-of-2` (discussed in [#9](https://github.com/mytakedotorg/us-presidential-debates/issues/9)).

## [1.1.0] - 2020-10-21
* *New event*: Added Biden Trump 1 of 3, 2020-09-29, transcription on YouTube parts [1](https://www.youtube.com/watch?v=qeqabiNXePM), [2](https://www.youtube.com/watch?v=2fxlZy5PvAU), [3](https://www.youtube.com/watch?v=-JtJnYUMxkY), [4](https://www.youtube.com/watch?v=QmyESfk3X6I), [5](https://www.youtube.com/watch?v=g_PIEISYz44), [6](https://www.youtube.com/watch?v=SlGO-iugPMM), [7](TODO), [8](https://www.youtube.com/watch?v=WYf3BbXcR3g). ([PR #8](https://github.com/mytakedotorg/us-presidential-debates/pull/8))

## [1.0.0] - 2020-10-06
* **Changed title of published fact**: every fact title began with `U.S. Presidential Debates - `, removed in ([955fd7f](https://github.com/mytakedotorg/us-presidential-debates/commit/955fd7f212c07a86341bd8e0ae8f1ff46bd6bbb2)).
* *Added detail*: added a `location` field for all the debates ([#7](https://github.com/mytakedotorg/us-presidential-debates/pull/7)).
  * Except `1960-10-13`, in which [Nixon was in LA while Kennedy was in NYC](https://github.com/mytakedotorg/us-presidential-debates/pull/7/commits/cf0d00688005c28485165b25c00fec738798e742#diff-fc33bd38ca325f4cbf616abd57f28378).
  * Also added metadata for the VP debates, in preparation for adding them in the future.

## [0.1.0] - 2020-09-29
* The initial version of the files in this repository were built in the `presidential-debates` folder of the [mtdo](https://github.com/mytakedotorg/mtdo/tree/prod/2019-04-15/presidential-debates) repository.
* We will try to bring the history from that subfolder into this in the future.
* But for now, we're shipping our first public version, so we're calling it 1.0 and working from here.

<!-- END CHANGELOG -->

# Acknowledgements
- Transcript for `Biden, Trump (1 of 2)` from [rev](https://www.rev.com/blog/transcripts/donald-trump-joe-biden-1st-presidential-debate-transcript-2020).
- Transcript for `Biden, Trump (2 of 2)` from [rev](https://www.rev.com/blog/transcripts/donald-trump-joe-biden-final-presidential-debate-transcript-2020).
- [The Commission on Presidential Debates](https://www.debates.org/) provides transcripts and metadata for the debates.
- [C-SPAN](https://www.c-span.org/) provides video footage.
