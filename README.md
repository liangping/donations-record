# donations-record

LOL has pledged the first month of mining, plus 25% of new mining for first 1,000 days.

## First Month

Autopay-Batch file used to donate first 30 days of mining by 46A7A, on 2021-3-10, epoch 99. Note: file formats have changed since.

```js
{
    "instructions": [
        { "_note": "engineering fund, iqlusion, https://github.com/iqlusioninc/0L-iqlusion-engineering-fund",
            "uid": 0, "destination": "C906F67F626683B77145D1F20C1A753B",  "percent_balance": 30, "end_epoch": 99, "duration_epochs": 30
        },
        { "_note": "humanitarian, red cross, https://github.com/Danish-Red-Cross-Humanitarian-Fund",
            "uid": 1, "destination": "B31BD7796BC113013A2BF6C3953305FD",  "percent_balance": 25, "end_epoch": 99, "duration_epochs": 30
        },
        { "_note": "app studio, newlab, https://github.com/blockchainnewlab/Application-Studio/",
            "uid": 2, "destination": "BC25F79FEF8A981BE4636AC1A2D6F587",  "percent_balance": 10, "end_epoch": 99, "duration_epochs": 30
        },
        { "_note": "moonshots, lol, https://github.com/LOL-LLC/moonshot-program",
            "uid": 3, "destination": "2057BCFB0189B7FD0ABA7244BA271661",  "percent_balance": 15, "end_epoch": 99, "duration_epochs": 30
        },
        { "_note": "tip jar, lol, https://github.com/LOL-LLC/tip-jar",
            "uid": 4, "destination": "2B0E8325DEA5BE93D856CFDE2D0CBA12",  "percent_balance": 5, "end_epoch": 99, "duration_epochs": 30
        },
        { "_note": "deep tech, blockscience, https://github.com/BlockScience/deep-technology-innovation-program",
            "uid": 5, "destination": "BB6926434D1497A559E4F0487F79434F",  "percent_balance": 5, "end_epoch": 99, "duration_epochs": 30
        },
        { "_note": "social experiments, radicalxchange, https://github.com/RadicalxChange/RxC-Research-and-Experimentation",
            "uid": 6, "destination": "C19C06A592911ED31C4100E9FB63AD7B",  "percent_balance": 5, "end_epoch": 99, "duration_epochs": 30
        },
        { "_note": "human rewards, human protocol, https://gist.github.com/posix4e/a17e72527fbb1cc4625c6bb84181ba71",
            "uid": 7, "destination": "E0484EA7FCF0694F79E484FC684E6C2C",  "percent_balance": 5, "end_epoch": 99, "duration_epochs": 30
        }
    ]
  }
```
* Note, for clarity the fields were updated to reflect the format of v4.3.0 json format. Previously `percent_balance` was named `percent_int`.


## Ongoing

File for reference: https://github.com/LOL-LLC/donations-record/blob/main/ongoing.autopay_batch.json


```js
{
  "autopay_instructions": [
    {
      "note": "engineering fund, iqlusion, https://github.com/iqlusioninc/0L-iqlusion-engineering-fund",
      "uid": 0,
      "destination": "C906F67F626683B77145D1F20C1A753B",
      "type_of": "PercentOfChange",
      "value": 4.75,
      "duration_epochs": 1000
    },
    {
      "note": "a good list, automated donations to non-profits, https://github.com/LOL-LLC/a-good-list",
      "uid": 1,
      "destination": "BCA50D10041FA111D1B44181A264A599",
      "type_of": "PercentOfChange",
      "value": 4.00,
      "duration_epochs": 1000
    },
    {
      "note": "fulltime engineers program, https://github.com/MSRG/0L-FTEP",
      "uid": 2,
      "destination": "1691A76AF070B76FD8E2F07CD39AFC49",
      "type_of": "PercentOfChange",
      "value": 3.75,
      "duration_epochs": 1000
    },
    {
      "note": "moonshots, lol, https://github.com/LOL-LLC/moonshot-program",
      "uid": 3,
      "destination": "2057BCFB0189B7FD0ABA7244BA271661",
      "type_of": "PercentOfChange",
      "value": 3.25,
      "duration_epochs": 1000
    },
    {
      "note": "humanitarian, red cross, https://github.com/Danish-Red-Cross-Humanitarian-Fund",
      "uid": 4,
      "destination": "B31BD7796BC113013A2BF6C3953305FD",
      "type_of": "PercentOfChange",
      "value": 2.50,
      "duration_epochs": 1000
    },
    {
      "note": "app studio, newlab, https://github.com/blockchainnewlab/Application-Studio/",
      "uid": 5,
      "destination": "BC25F79FEF8A981BE4636AC1A2D6F587",
      "type_of": "PercentOfChange",
      "value": 2.5,
      "duration_epochs": 1000
    },
    {
      "note": "tip jar, lol, https://github.com/LOL-LLC/tip-jar",
      "uid": 6,
      "destination": "2B0E8325DEA5BE93D856CFDE2D0CBA12",
      "type_of": "PercentOfChange",
      "value": 1.25,
      "duration_epochs": 1000
    },
    {
      "note": "deep tech, blockscience, https://github.com/BlockScience/deep-technology-innovation-program",
      "uid": 7,
      "destination": "BB6926434D1497A559E4F0487F79434F",
      "type_of": "PercentOfChange",
      "value": 1.25,
      "duration_epochs": 1000
    },
    {
      "note": "human rewards faucet, human protocol, https://gist.github.com/posix4e/a17e72527fbb1cc4625c6bb84181ba71",
      "uid": 8,
      "destination": "E0484EA7FCF0694F79E484FC684E6C2C",
      "type_of": "PercentOfChange",
      "value": 1.25,
      "duration_epochs": 1000
    },
    {
      "note": "social experiments, radicalxchange, https://github.com/RadicalxChange/RxC-Research-and-Experimentation",
      "uid": 9,
      "destination": "C19C06A592911ED31C4100E9FB63AD7B",
      "type_of": "PercentOfChange",
      "value": 0.5,
      "duration_epochs": 1000
    }
  ]
}
```
