
# 🔀 ASIOS™ Forking & Derivative Use Policy

## 1. Purpose & Scope  
Defines rules for creating and distributing forks or derivatives of **ASIOS™**, protecting licensing, trademarks, and proprietary assets.

---

## 2. License Preservation  
- Retain all original license headers in every source file.  
- Include full text of applicable licenses (GPL-2.0, GPL-3.0, AGPL-3.0, MIT, Apache-2.0) in a `LICENSES/` directory at project root.  
- AGPL-3.0 components disclosing network services must publish source code.

---

## 3. Attribution  
- In your `README.md` or UI, include:  
  > “Derived from ASIOS™ by KarLex AI, Inc.”  
- Clearly label your repository as an **Unofficial Fork** not endorsed by KarLex AI.

---

## 4. Upstream Compatibility  
- Maintain Debian-style patch series.  
- Regularly rebase against upstream `asi-os/asios` and Ubuntu 24.04 LTS.  
- Submit non-proprietary enhancements upstream via pull requests.

---

## 5. Multi-Architecture Compliance  
- Support and test on both x86_64 and ARM64.  
- Keep architecture-specific code under `arch/x86_64/` or `arch/arm64/`.  

---

## 6. Trademark & Branding  
- Do **not** use “ASIOS™”, KarLex AI logos, or trademarks without written consent.  
- Use distinct names, logos, and domains for your fork.

---

## 7. Proprietary Components Protection  
Do **not** fork, redistribute, or reverse-engineer proprietary modules such as:  
- Advanced scheduling or memory-tuning tools  
- Enterprise security and anomaly detectors  
- Cloud orchestration/telemetry SaaS modules  
- Constitutional AI frameworks  
- NVIDIA Grace CPU optimizations and related GPU acceleration  
- Proprietary AI training/inference systems

---

## 8. Kernel & Driver Compliance  
- Document all kernel or GPU driver changes.  
- Ensure compatibility with Linux kernel ABIs.  
- Preserve GPUDirect, RDMA, and driver support details.

---

## 9. Safety & Ethics  
- Retain built-in ethical guardrails (eBPF monitoring, constitutional AI checks).  
- Do not disable or weaken safety mechanisms.  
- Document ethical compliance across supported architectures.

---

## 10. Permitted vs. Restricted Activities  

**Permitted**  
- Non-commercial educational or research forks  
- Upstream submission of non-proprietary improvements  
- Complementary utilities, documentation, SDKs  
- Clearly labeled experimental projects  

**Restricted**  
- Commercial distribution without a KarLex AI license  
- Redistributing proprietary binaries or services  
- Implying official KarLex AI endorsement  
- Breaking multi-architecture compatibility  

---

## 11. Transparency Requirements  
Forks must include at project root:  
- `POLICY.md` (this file)  
- `CHANGELOG.md` (documenting deviations from upstream)  
- `LICENSES/` (all license texts)  
- `SECURITY.md` (security modifications)  
- `ARCHITECTURE.md` (supported hardware details)

---

## 12. Hardware Validation  
- Test on Intel/AMD x86_64, NVIDIA Grace, AWS Graviton, Apple M-series.  
- Publish benchmarks and compatibility data.  
- QEMU emulation is acceptable for initial validation.

---

## 13. Upstream Contribution Encouragement  
- Submit enhancements back to `asi-os/asios` upstream.  
- Follow Debian/Ubuntu packaging guidelines.  
- Engage via GitHub Discussions, the CSC, or relevant TWGs.

---

## 14. Compliance & Enforcement  
- Report violations to **legal@karlex.ai**.  
- KarLex AI may pursue DMCA, trademark actions, or contractual remedies under Delaware law.

---

## 15. Contacts  
- **Open-Source Licensing:** opensource@karlexai.com  
- **Commercial Licensing:** business@karlexai.com  
- **Architecture Support:** arm64@karlexai.com • x86_64@karlexai.com  
- **Legal & Trademarks:** legal@karlexai.com  

---

## 16. Forward-Looking Disclaimer  
This policy contains forward-looking statements—actual practices may evolve with KarLex AI’s growth.

---

*Full policy and related legal documents: [asios-legal](https://github.com/asi-os/asios-legal)*
