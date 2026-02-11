# Dune DEX Volume

Fetch DEX trading volume and statistics.

## Configuration

- **Blockchain**: arbitrum
- **Time Range**: 24h

## Usage

```tsx
import { useDEXVolume } from '@/hooks/useDEXVolume';

function VolumeChart() {
  const { data: volume } = useDEXVolume({
    blockchain: 'arbitrum',
    timeRange: '24h'
  });
  
  return <DEXVolumeChart data={volume} />;
}
```
