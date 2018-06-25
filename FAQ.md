# FAQ

## The `masternode outputs` return an empty object.
```
{
}
```

You must receive the **5000 CRAVE** for the **masternode** in a single transaction on your **Control Wallet** and wait for at least 1 confirmation.
> If you already have the **5000 CRAVE** but it came from multiple transactions, you can send the **5000 CRAVE** back to yourself:
```
docker exec crave-wallet crave-cli sendfrom "" YoUrAdDr3Ss CRAVE
```

## Running a **wallet** or a **masternode** container result in the following error:
```
No such file or directory
```

Ensure the `data` folder is *writable* for the container.
