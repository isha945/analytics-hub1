# Dune Gas Price Analytics

Fetch gas price analytics and statistics.

## Configuration

- **Blockchain**: arbitrum

## Usage

```tsx
import { useGasPrice } from '@/hooks/useGasPrice';

function GasTracker() {
  const { data: gas } = useGasPrice({
    blockchain: 'arbitrum'
  });
  
  return <GasPriceCard data={gas} />;
}
```
