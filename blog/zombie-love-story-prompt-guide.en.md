export const meta = {
  title: 'Zombie Love Story Prompt Guide (and Why Two Distinct Photos Matter)',
  description:
    'How the ZombieHug story binds Photo 1 and Photo 2, what goes wrong when both refs are the same person, and when to skip prompts entirely on aizombie.app.',
  created_at: '2026-10-07',
  author_name: 'ZombieHug',
  author_image: '/logo.png',
};

Most viral zombie hug clips fail for one boring reason: the model only sees **one identity**. If both reference frames are the same face (or two shots of the same demo character), the hug becomes a self-clone in matching clothes.

## On aizombie.app you usually do not write a prompt

[ZombieHug](https://aizombie.app) ships fixed story templates. You upload two photos; the server builds a Seedance 2.5 prompt that maps:

- **@image1 / Photo 1** → survivor who holds the gun
- **@image2 / Photo 2** → the loved one who turns (healthy again in the memory)

Optional note text only changes the **memory place**, not the plot.

## Photo checklist

1. Two **different** people (or person + pet for pet templates).
2. Clear faces, decent lighting, not a heavy crop of someone else’s viral frame.
3. One adult per human slot; pets only on Cat/Dog effects.
4. Own the likeness rights.

## If you still want a DIY prompt elsewhere

Keep both faces locked, time the leap cut, ban gore and gunfire, and force normal speed. Example skeleton:

> Exactly ~20s, vertical 9:16, photoreal, hard cuts, no slow-mo, no text. Person in photo 1 holds the gun; person in photo 2 has turned. Keep both faces stable. Present: abandoned cabin → lowers gun → open arms → leap. Hard cut on contact to a warm memory of the same two people. No blood, gun never fires.

For the no-prompt path, just use [Create on aizombie.app](https://aizombie.app).

## Related

- [How to make an AI zombie hug video](/blog/how-to-make-ai-zombie-hug-video)
- Demo: [/samples/sample.mp4](https://aizombie.app/samples/sample.mp4)
