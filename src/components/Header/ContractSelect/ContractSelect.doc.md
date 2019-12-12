With contracts: 

```jsx
<div style={{ background: '#4a4a4a' }}>
    <ContractSelect label="Contract" contracts={[{ id: '1046464' }, { id: '1045645' }, { id: '1555555543535345345g445' }]} selectedContractId={'1046464'} onChange={f => f} />
</div>
```


Without contracts:
```jsx
<div style={{ background: '#4a4a4a' }}>
    <ContractSelect label="Contract" contracts={[]} selectedContractId={'1046464'} onChange={f => f} />
</div>
```
