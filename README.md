
### Instructions

```bash
olac compile vote.ola
```

```bash
./olaws.sh encode -f "contract_init(u32[])" -a "[1,2,3]"
```

```bash
./olaws.sh execute contract_init
```

```bash
./olaws.sh encode -f "vote_proposal(u32)" -a 2
./olaws.sh execute vote_proposal
./olaws.sh encode -f "winningProposal()"
./olaws.sh execute winningProposal
```


Challenge
https://github.com/bilgin-kocak/ola-challange-1