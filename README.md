<div align="center">

# jasmid.ts

Fork of [jasmid](https://github.com/gasman/jasmid) MIDI file reader in TypeScript

</div>

## Install

```sh
npm i jasmid.ts
```

## Example
```js
import { parseMidiFile } from "jasmid.ts"

const midi = parseMidiFile(arrayBuffer)

// midi has type:
// {
//   header: { formatType: number; trackCount: number; ticksPerBeat: number };
//   tracks: MidiEvent[][];
// }

```

## API

See [src/index.ts](src/index.ts#L1).

## Donate

[By buying a beer](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=BCL2X3AFQBAP2&item_name=jasmid.ts%20Beer).
