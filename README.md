# Responsible AI at Corvamed

How the AI in Corvamed is designed: what it does, what it does not do and the rules we follow.

> **Stage:** Corvamed is in development. The service is not live yet. Everything below describes how we plan to build it, and it may change. We will update this page as the work moves on.

## What the AI does

- **Reads the trial rules.** Every trial has rules about who can take part, often pages of medical text. The AI breaks each rule into clear facts: age, diagnosis, stage, earlier treatment and reasons someone cannot take part.
- **Compares them with your situation.** You describe your situation in plain words, or upload your medical letters and the AI pulls out the facts that matter for trials. Each fact is compared with the trial rules.
- **Says when it is not sure.** When something is unclear, Corvamed says so instead of guessing.
- **Explains in plain words and in your language.** Each result explains what is being tested, where it takes place, what it asks of you, the known risks, the chance of a placebo and questions to take to your doctor. The original trial text stays one click away.
- **Lets you know about new trials.** If a trial that may fit you appears later, we tell you.

We plan to start with [CTIS](https://www.ema.europa.eu/en/human-regulatory-overview/research-development/clinical-trials-human-medicines/clinical-trials-information-system), the EU's public register of clinical trials, and with one disease area.

## What the AI does not do

- **No diagnosis, no treatment.** Corvamed does not give medical advice. Talk to your own doctor about any decision.
- **No final yes or no.** The AI does not decide whether you can take part in a trial.
- **No promises about results.** A trial is an experiment. The new treatment may not help, and you may receive a placebo.
- **No sharing without your decision.** Your details go to a trial site only after you say yes to that specific trial.
- **No paid ranking.** Payment never buys a better place in the results.

## Who decides

| Decision | Who makes it |
| --- | --- |
| Whether you can take part in a trial | Only the trial doctor, after their own checks |
| Whether your details go to a trial site | You, for each specific trial |
| Whether the matching is good enough to launch | Before launch, a doctor who runs trials checks how well the matching works |
| Any decision about your health | You and your own doctor |

## Data and consent

- **Health data is special.** Under the [GDPR](https://eur-lex.europa.eu/eli/reg/2016/679/oj), health data is a special category of personal data (Article 9). We will ask for your clear, explicit consent before we use it.
- **Only what is needed.** We will ask only for the facts that matter for matching, and explain why we need each one.
- **You decide who sees it.** Nothing goes to a trial site until you decide to contact that site.
- **Before the service handles any health data,** we will publish a separate, detailed privacy notice, ask for your explicit consent and have the processing reviewed by a lawyer.
- **Today:** the website uses no cookies, no analytics and no third-party scripts, and it does not collect health data. Please do not send medical records at this stage.

## Rules we are building for

These are the rules we commit to publicly:

- **Every suitable trial is shown.** Patients see all trials that may fit them, not only those of sponsors who work with us, whoever pays.
- **Risks are always explained.** Every result says plainly what taking part involves, including placebo and side effects.
- **Free for patients.** Patients will never pay to use Corvamed. Research teams pay.
- **GDPR.** Health data will be used only with your explicit consent.
- **EU Clinical Trials Regulation.** We explain to patients that in the EU, participants generally do not pay for the medicine being tested or for procedures the trial requires ([Regulation (EU) No 536/2014](https://eur-lex.europa.eu/eli/reg/2014/536/oj), Article 92).
- **Local rules are respected.** Rules for advertising clinical trials differ from country to country. We will work with a lawyer in pharmaceutical law in each country.

## Contact

Questions or ideas about how the AI should work: [info@corvamed.com](mailto:info@corvamed.com) or open an issue in this repository. Questions about personal data: [privacy@corvamed.com](mailto:privacy@corvamed.com).

Please never include real personal or health data in issues.

Website: [corvamed.com](https://corvamed.com) · LinkedIn: [Corvamed](https://linkedin.com/company/corvamed) · X: [@corvamedcompany](https://x.com/corvamedcompany)

## Licence

The text in this repository is licensed under the [Creative Commons Attribution 4.0 International licence (CC BY 4.0)](LICENSE). The Corvamed name and logo are not covered by this licence.
