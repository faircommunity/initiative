# Is FCL Open Source?

The short answer is: **It depends on the version, but generally, No.**

To maintain transparency with the developer community, it is important to clarify the distinction between the **Fair Community License (FCL)** and the formal definition of "Open Source."

---

## 1. The OSI Definition

The [Open Source Initiative (OSI)](https://opensource.org/osd) maintains the **Open Source Definition**, which consists of 10 criteria. Most FCL variants (Strict, Standard, and Light) do not comply with **Criterion 6: No Discrimination Against Fields of Endeavor**.

By restricting specific commercial behaviors—such as offering the software as a managed service (SaaS)—these licenses do not meet the formal requirements to be labeled as "Open Source."

---

## 2. The FCL Spectrum

The FCL initiative is a family of licenses. Not all of them occupy the same space:

- **FCL-Open:** Intended to be Open Source–compatible. This version is permissive and aligned with open-source principles. It has no commercial or SaaS restrictions.
- **FCL-Strict, Standard, and Light:** **No.** These are **Fair Community** licenses. They provide public access to the source code and allow modification, but they introduce commercial boundaries to support project sustainability.
- **FCL-Evolution:** **Eventually.** This model starts as Fair Community and automatically converts to a permissive FCL-Open license after a defined period.

---

## 3. Why Not Call It Open Source?

We respect the Open Source movement and the clarity the OSI definition provides. Attempting to redefine Open Source to include commercial restrictions leads to confusion and "openwashing."

Instead, we categorize the protective FCL variants as **Fair Community**.

| Feature | Open Source (e.g., MIT/Apache) | Fair Community (e.g., FCL-Standard) |
|:--- |:--- |:--- |
| **Public Source Code** | ✅ Yes | ✅ Yes |
| **Right to Modify** | ✅ Yes | ✅ Yes |
| **Free for Personal Use** | ✅ Yes | ✅ Yes |
| **Free for Internal Tooling** | ✅ Yes | ✅ Yes |
| **Free SaaS/Managed Use** | ✅ Yes | ❌ No (Requires License) |
| **"Primary Asset" Resale** | ✅ Yes | ❌ No (Requires License) |

---

## 4. Sustainability vs. Frictionless Freedom

The distinction exists because of a fundamental difference in goals:

- **Open Source** (like Apache 2.0) optimizes for **maximum frictionless adoption**.
- **Fair Community** (like FCL-Standard) optimizes for **long-term sustainability** in environments where large-scale commercial operators may monetize projects without proportionate support.

---

## 5. Conclusion

FCL is not an attempt to replace Open Source. It is an **architectural expansion** of the licensing landscape.

If your project requires full compliance with the Open Source Definition, use **FCL-Open** (where appropriate) or a traditional license like **Apache 2.0**.

If your project requires a sustainable commercial model that still empowers developers and ensures future openness, the **FCL family** was built for you.

---

"Open Source made code available. Fair Community ensures the people who build that code can afford to keep building."