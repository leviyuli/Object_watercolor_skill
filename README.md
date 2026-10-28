# Object Watercolor

A Codex skill for translating photographs into small, naive watercolor-and-crayon sketches on warm off-white paper, with generous whitespace. It preserves the subject's identity, pose, action, expression, and essential scene relationships.

将照片转译为米白旧纸上的小幅稚拙水彩手绘：少量色块、蜡笔线条、低饱和配色、大面积留白，并保留原本主体、动作、表情与情境。

## Skill

- Name: `object-watercolor`
- Instructions: [object-watercolor/SKILL.md](object-watercolor/SKILL.md)
- Default format: square, one illustration per content photo unless requested otherwise.
- An optional approved style reference supplies only visual logic; it does not supply subjects, props, actions, text, or composition details.

## Install in Codex

Ask Codex:

> Use skill-installer to install object-watercolor from https://github.com/leviyuli/Object_watercolor_skill, path object-watercolor.

The standard installer command is:

```text
python <skill-installer>/scripts/install-skill-from-github.py --repo leviyuli/Object_watercolor_skill --path object-watercolor
```

The default destination is `$CODEX_HOME/skills/object-watercolor`, or `~/.codex/skills/object-watercolor` when `CODEX_HOME` is unset. The skill becomes available on the next turn after installation.

## Use

Attach a photograph and ask:

> Use $object-watercolor to turn this photo into a small, abstract watercolor-and-crayon sketch. Preserve the original pose, expression, and key objects, with plenty of off-white paper space.

Or:

> 用 $object-watercolor 把这张照片画成小幅稚拙水彩速写，保留原本动作、神情与场景关系，四周大面积留白。

The skill uses the available image-generation tool. This repository contains the reusable instructions and UI metadata; no personal source photos or generated examples are bundled.
