# Operations Workshop

## Initial Setup

**Step 1**

Clone this repository.

```bash
git clone https://github.com/ecwpz91/operations-workshop.git
```

**Step 2**

Change your current directory to the cloned repository.

```bash
cd operations-workshop/
```

> **NOTE:** The following sections of documentation will assume that you are in
> the root directory of the clone repository.

## AWS Credentials

In order to follow the steps below, you need to export your AWS credentials and
the region to use.

If you already have a profile setup using the `awscli`, you can export
`AWS_PROFILE`.

```bash
export AWS_PROFILE=default
export AWS_REGION=us-east-1
```

Otherwise, export `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY`.

```bash
export AWS_ACCESS_KEY_ID=access_key
export AWS_SECRET_ACCESS_KEY=secret-key
export AWS_REGION=us-east-1
```
