# My Presets for EasyEffects

> [!NOTE]
>
> These settings are subjective, people don't all hear the same things in the same way. While the settings
> in these presets achieve the type of sound I desire when I listen to music, they may not fit the type of
> sound you like when listening to music. Feel free to adapt things to your own preferences and to your ears.

## Design of presets (explanation and ordering of effects)

The included presets are based partially on [Digitalone1's Loudness Equalizer Presets](https://www.github.com/Digitalone1/EasyEffects-Presets)
and generally follow the same layout and ordering when it comes to the effects that are applied,
with some changes/tweaks, targeted mainly to prioritize music listening while retaining dynamics as
much as possible.

Presets generally consist of the following effects (applied in this order, if present):

#### Filters

Usually configured as two filters, first a high pass to cut out frequencies below a certain level, and then
a low pass applied after to cut out upper frequencies.

These are applied to limit the overall frequency range of the output to prevent over-driving
speakers/headphones and to limit frequencies that are either not reproducible by the speakers/headphones
being used, are not audible or that are distracting/annoying to the listener.

#### Gate

Used to remove unwanted low-level background noise/hiss/static from the input so that it is not passed on to
the next stage of the effects chain (compressor) to avoid being boosted/amplified unnecessarily.

#### Upward Compressor

This is what raises the level of quiet parts of the input signal so they are more audible, it does however
reduce some amount of dynamic range which is corrected/minimized as much as possible by the rest of
the effects chain. This is different from normal compression, which works in the opposite manner, by making
the loud parts of the audio quieter.

#### Multiband Compressor

Used to lightly control the dynamic range of the output, by gently compressing different frequency bands
individually, giving more precise control over how different parts of the spectrum are treated and helping to
smooth out volume differences across each frequency range. Excessive use of this type of compression can
reduce audio quality noticeably, so the presets favor a relatively low compression ratio to help preserve
clarity.

#### Equalizer

The secret sauce and the most subjective part of these presets, the settings used here are highly personal
and should be treated as a general guideline only. This is most likely where you will do the majority of
any adjustments you make to the preset(s). The particular sound I like when listening to a broad range of
music may not fit your taste.

Generally my equalizer settings could be possibly considered somewhat aggressive, I try to emphasize the
low-end frequencies as much as possible without creating excessive booming/thumping, maintain warmth
in the mid-range without making things sound thin/muddy, and make the highs as crisp/bright as I think is
necessary to still sound good without creating undesirable stress on my ears when listening.

#### Bass Loudness (all presets except Speakers) / Loudness (only used in Speakers preset)

Bass Loudness is completely optional and disabled by default in all presets that use it, and can be enabled
to give a small, but nice enhancement to the bass frequencies if desired.

The Speakers preset uses the Loudness effect instead which uses equal loudness contours to target frequency
boosts/cuts based on the configured calibrated peak output desired from the speaker system being used.
This ensures that all frequencies are perceived equally as loud by the listener, which helps when listening to
music at lower volumes (such as at night).

#### Level Meter

Disabled by default in all presets, can be enabled to monitor the dynamics of the output and used as a tool
to help make adjustments to other effects if necessary.

#### Limiter

This effect is used as a last line of defense to prevent clipping of the output caused by sudden changes in the
input source volume caused by things such as poorly mixed audio, resulting in increased chances of distortion
being introduced by the other effects used above.

Ideally you never want the output to exceed 0db in any situation as this could damage your speakers/headphones.
I use a slightly more conservative threshold setting of -1db to ensure that the limiter always takes effect as
early and quickly as possible in these situations.

#### Crossfeed (only used in Headphones presets)

Completely optional, can be disabled if not desired. This effect helps to simulate the natural spatial effects
of listening to music through speakers, and can make long listening sessions using headphones more comfortable
and easier on your ears.

## Included presets

### Speakers

#### Speakers (Default)

General preset for speakers, designed to work best with small bookshelf speakers or a mini-system.

#### Laptop Speakers (Default)

Preset targeted at laptop speakers, designed mainly for my laptop (Lenovo ThinkPad Edge E540), may or may
not work well for other similar ThinkPad models. Designed to enhance bass as much as possible without creating
distortion or negatively effecting other frequencies.

### Headphones

#### LG Tone Free FP5 (Default / Reference EQ)

#### Sony MDR-XB950N1 (Default / Reference EQ)
