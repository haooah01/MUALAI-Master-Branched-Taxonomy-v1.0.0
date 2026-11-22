# MUALAI — MUA LẠI DOANH NGHIỆP
## Master Branched Taxonomy v1.0.0

**Project ID:** THH-MUALAI-v1.0.0  
**Namespace:** thh  
**Author:** Trần Thế Hảo  
**Status:** Structured reference / educational taxonomy  
**Legal snapshot:** Vietnam law checked against consolidated legal texts available on 22 November 2026  
**Scope:** Acquisition of a business, company, equity, assets, business units, debt claims, intellectual property, or control rights.

---

## 0. CÁCH ĐỌC HỆ THỐNG

MUALAI được phân nhánh theo các trục độc lập. Một thương vụ có thể thuộc nhiều nhánh cùng lúc; không ép một thương vụ vào duy nhất một nhãn.

**Phân biệt nền tảng:**
- **Acquisition:** giao dịch tiếp nhận cổ phần, tài sản, hoạt động kinh doanh hoặc quyền kiểm soát của một chủ thể khác.
- **Buyout:** giao dịch mua toàn bộ hoặc một phần đủ để tiếp nhận/thiết lập quyền kiểm soát; không mặc định phải mua 100%.
- **Takeover:** nhấn mạnh sự thay đổi quyền kiểm soát; có thể thân thiện hoặc thù địch.
- **Buyback / Share Repurchase:** doanh nghiệp mua lại cổ phiếu/chứng khoán do chính mình phát hành. Đây là nhánh liên quan nhưng không đồng nghĩa với “mua lại doanh nghiệp”.
- **Insider:** mô tả quan hệ của người mua với doanh nghiệp mục tiêu; không phải một mức tỷ lệ sở hữu. Tỷ lệ sở hữu và quyền kiểm soát là trục riêng.

**Quy tắc phân loại:**
1. Ai mua? (Actor)
2. Mua cái gì? (Target)
3. Mua bao nhiêu quyền sở hữu/quyền biểu quyết? (Ownership & Control)
4. Bên mục tiêu có đồng thuận không? (Transaction Stance)
5. Giao dịch được cấu trúc như thế nào? (Deal Structure)
6. Dùng nguồn vốn nào? (Financing)
7. Mục tiêu kinh tế là gì? (Strategic Motive)
8. Sau giao dịch ai quản trị, tích hợp và thoái vốn? (Governance, Integration & Exit)

---

# MUALAI — MASTER BRANCH TREE

MUALAI (MUA LẠI DOANH NGHIỆP / BUSINESS ACQUISITION & BUYOUT)
│
├── 1. LEVELS OF OWNERSHIP & CONTROL (PHÂN THEO TỶ LỆ SỞ HỮU VÀ QUYỀN LỰC)
│   │
│   ├── LEVEL 1 — MINORITY STAKE (< 50%)
│   │   │
│   │   ├── 1A. Dưới 5%
│   │   │   ├── Small / Portfolio Stake: khoản sở hữu nhỏ; thường thiên về đầu tư tài chính.
│   │   │   ├── Không mặc định có quyền tham gia điều hành hoặc quyền đề cử.
│   │   │   └── Vẫn có quyền cổ đông cơ bản theo loại cổ phần, điều lệ và pháp luật.
│   │   │
│   │   ├── 1B. Từ 5% đến dưới 10%
│   │   │   ├── Public-company Large Shareholder: từ 5% cổ phiếu có quyền biểu quyết tại tổ chức phát hành thuộc phạm vi Luật Chứng khoán.
│   │   │   ├── Có thể phát sinh nghĩa vụ công bố thông tin khi trở thành/không còn là cổ đông lớn và khi tỷ lệ sở hữu thay đổi qua ngưỡng luật định.
│   │   │   ├── Theo Luật Doanh nghiệp, cổ đông/nhóm cổ đông đạt từ 5% cổ phần phổ thông (hoặc tỷ lệ thấp hơn tại Điều lệ) có một số quyền tiếp cận hồ sơ, yêu cầu triệu tập ĐHĐCĐ trong trường hợp luật định và yêu cầu Ban kiểm soát kiểm tra.
│   │   │   └── Không mặc định có quyền đề cử HĐQT/BKS theo ngưỡng mặc định 10%.
│   │   │
│   │   ├── 1C. Từ 10% đến dưới 25%
│   │   │   ├── Significant Minority Stake: cổ phần thiểu số có ảnh hưởng đáng kể.
│   │   │   ├── Theo Luật Doanh nghiệp, cổ đông/nhóm cổ đông đạt từ 10% cổ phần phổ thông (hoặc tỷ lệ thấp hơn theo Điều lệ) có quyền đề cử người vào HĐQT/BKS theo điều kiện luật định.
│   │   │   └── Quyền đề cử không đồng nghĩa chắc chắn bầu được ứng viên hoặc kiểm soát công ty.
│   │   │
│   │   ├── 1D. Từ 25% đến dưới 35%
│   │   │   ├── Strategic / Blocking-Potential Minority: vị thế thiểu số có thể tạo ảnh hưởng lớn tùy phân bổ quyền biểu quyết.
│   │   │   ├── Với công ty đại chúng, dự kiến mua đạt từ 25% cổ phiếu có quyền biểu quyết thường thuộc trường hợp phải thực hiện chào mua công khai, trừ ngoại lệ luật định.
│   │   │   └── Không tự động trở thành cổ đông kiểm soát.
│   │   │
│   │   └── 1E. Từ 35% đến dưới 50%
│   │       ├── High Minority / Potential Blocking Position.
│   │       ├── Có thể ngăn một nghị quyết cần tỷ lệ tán thành cao nếu số phiếu phản đối vượt phần còn lại cần thiết; kết quả phụ thuộc số người dự họp, số phiếu biểu quyết thực tế, loại nghị quyết và Điều lệ.
│   │       └── Không gọi đây là “quyền phủ quyết tự động 35%” theo Luật Doanh nghiệp.
│   │
│   ├── LEVEL 2 — MAJORITY / CONTROLLING STAKE (> 50% đến dưới 65%)
│   │   ├── Majority Voting Position: thường có khả năng thông qua nghị quyết thông thường nếu nắm đa số phiếu biểu quyết hợp lệ và điều kiện họp/biểu quyết được đáp ứng.
│   │   ├── Có thể tạo quyền kiểm soát thực tế đối với bổ nhiệm, chiến lược và hoạt động quản trị, tùy mô hình công ty và Điều lệ.
│   │   └── Không mặc định thông qua được mọi nghị quyết đặc biệt cần tỷ lệ cao hơn.
│   │
│   ├── LEVEL 3 — SUPERMAJORITY STAKE (từ 65% đến dưới 100%)
│   │   ├── Có thể đáp ứng ngưỡng biểu quyết 65% cho một số nghị quyết quan trọng tại ĐHĐCĐ công ty cổ phần theo quy tắc mặc định của Luật Doanh nghiệp.
│   │   ├── Ngưỡng 65% được tính trên tổng số phiếu biểu quyết của cổ đông tham dự và biểu quyết tại cuộc họp đối với nhóm vấn đề luật định; Điều lệ có thể quy định tỷ lệ cụ thể khác trong phạm vi pháp luật cho phép.
│   │   ├── Sở hữu 65% vốn/cổ phần không đồng nghĩa “toàn quyền thông qua mọi vấn đề” trong mọi cấu trúc công ty.
│   │   └── Phải kiểm tra loại cổ phần, quyền biểu quyết, họp/lấy ý kiến bằng văn bản, Điều lệ, quy định chuyên ngành và giao dịch với bên liên quan.
│   │
│   └── LEVEL 4 — FULL ACQUISITION / 100% OWNERSHIP
│       │
│       ├── 4A. Share Acquisition — 100% Equity, Legal Entity Continues
│       │   ├── Bên mua tiếp nhận toàn bộ cổ phần/phần vốn góp.
│       │   ├── Pháp nhân mục tiêu về nguyên tắc vẫn tồn tại riêng; tài sản, hợp đồng và nghĩa vụ tiếp tục nằm trong pháp nhân mục tiêu.
│       │   ├── Có thể xem xét chuyển đổi sang công ty TNHH một thành viên nếu đáp ứng điều kiện và thực hiện thủ tục pháp lý tương ứng.
│       │   └── Không mặc định 100% cổ phần tự động làm thay đổi loại hình pháp lý ngay tại thời điểm mua.
│       │
│       ├── 4B. Merger / Statutory Merger — Sáp nhập, pháp nhân bị sáp nhập chấm dứt
│       │   ├── Một hoặc nhiều công ty chuyển toàn bộ tài sản, quyền, nghĩa vụ và lợi ích hợp pháp sang công ty nhận sáp nhập.
│       │   ├── Công ty bị sáp nhập chấm dứt tồn tại theo trình tự và thời điểm pháp luật quy định.
│       │   └── Đây là tái tổ chức doanh nghiệp; không đồng nhất với việc chỉ mua 100% cổ phần.
│       │
│       └── 4C. 100% Asset Acquisition
│           ├── Mua toàn bộ hoặc gần như toàn bộ nhóm tài sản/hoạt động được xác định.
│           └── Không nhất thiết mua cổ phần hoặc tiếp nhận toàn bộ pháp nhân mục tiêu.
│
├── 2. CÁC CẤP MUA LẠI THEO NGƯỜI MUA, MỨC ĐỘ ĐỒNG THUẬN VÀ CƠ CHẾ THÂU TÓM
│   │
│   ├── 2A. THEO MỨC ĐỘ ĐỒNG THUẬN (TRANSACTION STANCE)
│   │   ├── Friendly Acquisition / Friendly Takeover
│   │   │   ├── Ban lãnh đạo/HĐQT hoặc cổ đông mục tiêu ủng hộ giao dịch.
│   │   │   └── Hai bên phối hợp đàm phán, thẩm định, phê duyệt và chuyển giao.
│   │   ├── Hostile Takeover
│   │   │   ├── Bên mua tìm cách giành quyền kiểm soát dù ban lãnh đạo mục tiêu phản đối.
│   │   │   ├── Có thể tiếp cận cổ đông thông qua tender offer hoặc các phương thức hợp pháp khác.
│   │   │   └── “Hostile” mô tả thái độ/quan hệ với ban lãnh đạo mục tiêu, không tự động có nghĩa giao dịch trái pháp luật.
│   │   └── Contested / Unsolicited Acquisition
│   │       ├── Đề nghị mua không được mời gọi hoặc có tranh chấp về điều kiện.
│   │       └── Có thể chuyển thành thân thiện hoặc thù địch trong quá trình giao dịch.
│   │
│   ├── 2B. THEO QUAN HỆ CỦA NGƯỜI MUA VỚI DOANH NGHIỆP (BUYER IDENTITY)
│   │   ├── Insider-led Buyout
│   │   │   ├── MBO — Management Buyout: đội ngũ quản lý hiện tại mua lại doanh nghiệp/bộ phận mình đang điều hành.
│   │   │   ├── MBI — Management Buy-in: đội ngũ quản lý bên ngoài mua lại và tiếp quản doanh nghiệp.
│   │   │   ├── BIMBO — Buy-in Management Buyout: kết hợp quản lý hiện tại và quản lý từ bên ngoài.
│   │   │   ├── EBO — Employee Buyout: nhân viên hoặc tập thể người lao động tham gia mua lại.
│   │   │   ├── Founder Buyout: nhà sáng lập mua lại phần sở hữu của đồng sáng lập/đối tác/cổ đông khác.
│   │   │   ├── Owner / Shareholder Buyout: chủ sở hữu hoặc cổ đông mua lại phần vốn của các chủ sở hữu/cổ đông còn lại.
│   │   │   └── Management-led Buyout: tên gọi mô tả nhóm quản lý dẫn dắt; có thể đồng thời là MBO, BIMBO hoặc sponsor-backed.
│   │   ├── External Strategic Buyer
│   │   │   ├── Doanh nghiệp cùng ngành hoặc khác ngành mua để tạo lợi thế chiến lược.
│   │   │   └── Có thể là đối thủ, nhà cung cấp, khách hàng hoặc doanh nghiệp mở rộng hệ sinh thái.
│   │   ├── Financial Sponsor / Private Equity Buyer
│   │   │   ├── Quỹ PE, quỹ đầu tư hoặc nhà tài trợ tài chính mua nhằm tạo giá trị và thoái vốn.
│   │   │   ├── Sponsor-backed Buyout: thương vụ có quỹ/tổ chức tài trợ hoặc dẫn dắt.
│   │   │   ├── Institutional Buyout (IBO): tổ chức đầu tư là bên mua chủ đạo.
│   │   │   └── Club Deal / Consortium Buyout: nhiều quỹ/nhà đầu tư cùng tham gia.
│   │   └── Hybrid Buyer Group
│   │       ├── Insider + PE Sponsor.
│   │       ├── Management + Strategic Investor.
│   │       └── Investor Consortium + Management Team.
│   │
│   ├── 2C. THEO CHIẾN LƯỢC ĐẦU TƯ / KIỂU BUYOUT
│   │   ├── LBO — Leveraged Buyout: mua lại với tỷ trọng nợ đáng kể trong cấu trúc tài trợ.
│   │   ├── MBO + LBO: quản lý hiện tại là người mua/đồng mua và giao dịch sử dụng đòn bẩy nợ.
│   │   ├── Sponsor-backed MBO: nhóm quản lý hiện tại kết hợp với quỹ/tổ chức tài trợ.
│   │   ├── Secondary Buyout: một quỹ PE bán doanh nghiệp danh mục cho quỹ PE khác.
│   │   ├── Tertiary / Subsequent Buyout: doanh nghiệp tiếp tục được chuyển nhượng qua các vòng buyout tiếp theo.
│   │   ├── Public-to-Private / Take-private: mua công ty đại chúng để đưa ra khỏi trạng thái niêm yết/đại chúng theo quy định.
│   │   ├── Divisional Buyout: mua lại một bộ phận kinh doanh/division.
│   │   ├── Carve-out Buyout: mua đơn vị được tách ra khỏi công ty mẹ.
│   │   ├── Distressed Buyout: mua doanh nghiệp đang gặp khó khăn tài chính.
│   │   └── Turnaround Buyout: mua để tái cấu trúc và phục hồi hoạt động.
│   │
│   └── 2D. CÔNG CỤ/PHƯƠNG THỨC TIẾP CẬN CỔ ĐÔNG
│       ├── Negotiated Acquisition: đàm phán riêng với bên bán/cổ đông.
│       ├── Tender Offer: chào mua công khai theo cơ chế áp dụng.
│       ├── Open-market Purchase: mua trên thị trường giao dịch.
│       ├── Block Trade: giao dịch khối lượng lớn theo cơ chế phù hợp.
│       ├── Auction Acquisition: mua thông qua đấu giá.
│       └── Proxy Contest: vận động quyền biểu quyết/ủy quyền để thay đổi quyền quản trị; không tự nó đồng nghĩa với mua cổ phần.
│
├── 3. CÁC CẤP MUA LẠI THEO ĐỐI TƯỢNG VÀ PHẠM VI TÀI SẢN (TARGET / DEAL PERIMETER)
│   │
│   ├── 3A. Share Deal / Equity Acquisition
│   │   ├── Mua cổ phần công ty cổ phần hoặc phần vốn góp của công ty trách nhiệm hữu hạn.
│   │   ├── Pháp nhân mục tiêu tiếp tục sở hữu tài sản và chịu các nghĩa vụ của chính mình.
│   │   ├── Bên mua nhận quyền kinh tế/quyền quản trị tương ứng với phần vốn và loại quyền được mua.
│   │   └── Due diligence phải kiểm tra nợ, thuế, kiện tụng, nghĩa vụ tiềm ẩn, hợp đồng, giấy phép, quyền sở hữu và giao dịch liên quan.
│   │
│   ├── 3B. Asset Deal / Asset Acquisition
│   │   ├── Mua một hoặc một nhóm tài sản được xác định: nhà máy, máy móc, bất động sản, thương hiệu, công nghệ, hàng tồn kho, dữ liệu hoặc quyền tài sản.
│   │   ├── Có thể giới hạn phạm vi tài sản và nghĩa vụ được tiếp nhận theo hợp đồng/pháp luật.
│   │   ├── Không mặc định “mua tài sản thì không nhận bất kỳ khoản nợ hay nghĩa vụ cũ nào”.
│   │   └── Phải kiểm tra quyền sở hữu, thế chấp, quyền của bên thứ ba, hợp đồng chuyển giao, thuế, lao động, môi trường, đất đai và điều kiện giấy phép.
│   │
│   ├── 3C. Business / Division Acquisition
│   │   ├── Mua một đơn vị kinh doanh, chi nhánh, division, dây chuyền hoặc nhóm hoạt động.
│   │   ├── Có thể triển khai theo Asset Deal, Share Deal của công ty con hoặc cấu trúc carve-out.
│   │   └── Cần xác định ranh giới tài sản, nhân sự, hợp đồng, hệ thống và nghĩa vụ được chuyển giao.
│   │
│   ├── 3D. Subsidiary Acquisition
│   │   ├── Mua công ty con hoặc công ty thành viên.
│   │   └── Phải phân tích cả nghĩa vụ ở cấp công ty con và rủi ro liên kết với công ty mẹ/tập đoàn.
│   │
│   ├── 3E. Debt / Claim Acquisition
│   │   ├── Mua khoản vay, trái phiếu, khoản phải thu hoặc quyền đòi nợ.
│   │   ├── Debt Purchase không tự động chuyển thành quyền sở hữu doanh nghiệp.
│   │   └── Debt-to-Control có thể phát sinh qua tái cấu trúc, chuyển đổi nợ thành vốn hoặc thực thi bảo đảm theo pháp luật.
│   │
│   ├── 3F. Intellectual Property / Technology Acquisition
│   │   ├── Mua/chuyển nhượng bằng sáng chế, nhãn hiệu, bản quyền, phần mềm, dữ liệu, bí quyết hoặc giấy phép sử dụng.
│   │   └── Cần phân biệt chuyển quyền sở hữu với cấp quyền sử dụng (license).
│   │
│   ├── 3G. Acqui-hire
│   │   ├── Mua doanh nghiệp chủ yếu để tiếp nhận đội ngũ nhân sự/tài năng cốt lõi.
│   │   ├── Đây là nhãn mô tả động cơ giao dịch; cấu trúc pháp lý có thể là Share Deal, Asset Deal hoặc tuyển dụng/chuyển giao nhân sự theo thỏa thuận.
│   │   └── Không mặc định toàn bộ nhân viên tự động chuyển sang bên mua; phải xử lý hợp đồng lao động và quyền của người lao động.
│   │
│   └── 3H. Merger / Consolidation
│       ├── Merger: một hoặc nhiều công ty sáp nhập vào một công ty nhận sáp nhập.
│       ├── Consolidation: các chủ thể hợp nhất để hình thành một pháp nhân mới theo cấu trúc pháp luật áp dụng.
│       └── Cần phân biệt với việc một bên mua cổ phần nhưng pháp nhân mục tiêu vẫn tồn tại.
│
├── 4. FINANCING BRANCH (NGUỒN VỐN & CẤU TRÚC TÀI TRỢ)
│   ├── Equity Financing: vốn chủ sở hữu của bên mua/nhà đầu tư.
│   ├── Debt Financing: khoản vay hoặc công cụ nợ.
│   ├── Senior Debt: nợ có thứ tự ưu tiên cao hơn theo hợp đồng/cấu trúc bảo đảm.
│   ├── Mezzanine Financing: vốn trung gian có đặc tính nợ và/hoặc quyền chuyển đổi.
│   ├── High-Yield Debt: nợ lãi suất cao, thường có rủi ro tín dụng cao hơn.
│   ├── Unitranche Financing: cấu trúc một khoản tài trợ kết hợp các lớp rủi ro/nợ.
│   ├── Seller Note / Vendor Financing: bên bán cho bên mua vay hoặc hoãn nhận một phần giá mua.
│   ├── Rollover Equity: người bán/nhà quản lý tái đầu tư một phần giá trị vào cấu trúc sở hữu mới.
│   ├── Co-investment: nhà đầu tư cùng góp vốn với sponsor.
│   ├── Bridge Financing: khoản tài trợ chuyển tiếp.
│   └── LBO STRUCTURE
│       ├── Buyer / Sponsor thành lập Acquisition Vehicle (BidCo/NewCo) nếu cần.
│       ├── BidCo huy động Equity + Debt để thanh toán giá mua.
│       ├── Sau Closing, cấu trúc nợ có thể được tái cơ cấu hoặc phân bổ theo tài liệu giao dịch và pháp luật.
│       └── Tài sản của Target không tự động trở thành tài sản bảo đảm cho khoản vay mua cổ phần; việc bảo đảm/ bảo lãnh cần có căn cứ, thẩm quyền, lợi ích doanh nghiệp và tuân thủ pháp luật.
│
├── 5. DEAL STRUCTURE & PAYMENT (CẤU TRÚC PHÁP LÝ VÀ THANH TOÁN)
│   ├── Cash Acquisition: thanh toán bằng tiền.
│   ├── Stock-for-Stock Acquisition: dùng cổ phiếu của bên mua để thanh toán.
│   ├── Mixed Consideration: kết hợp tiền, cổ phiếu hoặc công cụ khác.
│   ├── Earn-out: một phần giá mua phụ thuộc kết quả/điều kiện trong tương lai.
│   ├── Escrow / Holdback: giữ lại một phần tiền để bảo đảm nghĩa vụ sau Closing.
│   ├── Seller Financing: người bán tài trợ một phần giá mua.
│   ├── Rollover Equity: người bán giữ/tái đầu tư một phần quyền sở hữu.
│   ├── Asset Purchase Agreement (APA): hợp đồng mua bán tài sản.
│   ├── Share Purchase Agreement (SPA): hợp đồng mua bán cổ phần/phần vốn.
│   ├── Merger Agreement: thỏa thuận sáp nhập.
│   └── Conditions Precedent: điều kiện tiên quyết phải hoàn thành trước Closing.
│
├── 6. STRATEGIC MOTIVE (ĐỘNG CƠ KINH TẾ / CHIẾN LƯỢC)
│   ├── Horizontal Acquisition: mua doanh nghiệp cùng ngành/cùng tầng giá trị.
│   ├── Vertical Acquisition: mua nhà cung cấp hoặc khách hàng trong chuỗi giá trị.
│   ├── Conglomerate Acquisition: mua doanh nghiệp ở ngành/lĩnh vực khác.
│   ├── Platform Acquisition: mua doanh nghiệp nền tảng để mở rộng quy mô.
│   ├── Add-on / Bolt-on Acquisition: mua doanh nghiệp/tài sản bổ trợ cho nền tảng hiện hữu.
│   ├── Roll-up / Buy-and-Build: mua nhiều doanh nghiệp phân mảnh rồi hợp nhất.
│   ├── Technology Acquisition: tiếp nhận công nghệ/IP/năng lực R&D.
│   ├── Market-entry Acquisition: mua để vào thị trường, địa bàn hoặc phân khúc mới.
│   ├── Talent Acquisition / Acqui-hire: tiếp nhận đội ngũ nhân sự chủ chốt.
│   ├── Synergy Acquisition: khai thác cộng hưởng doanh thu, chi phí, công nghệ hoặc phân phối.
│   ├── Succession Buyout: giải quyết chuyển giao thế hệ/chủ sở hữu.
│   └── Distressed / Turnaround Acquisition: mua để tái cấu trúc, phục hồi hoặc xử lý tình huống khó khăn.
│
├── 7. GOVERNANCE, DUE DILIGENCE & REGULATORY (QUẢN TRỊ, THẨM ĐỊNH VÀ PHÁP LÝ)
│   ├── Ownership Verification: xác minh chủ sở hữu pháp lý và chủ sở hữu hưởng lợi cuối cùng.
│   ├── Cap Table: bảng vốn/cổ đông trước và sau giao dịch.
│   ├── Voting Rights: xác minh quyền biểu quyết, cổ phần ưu đãi và thỏa thuận cổ đông.
│   ├── Corporate Due Diligence: tư cách pháp lý, điều lệ, nghị quyết, quyền ký và thẩm quyền phê duyệt.
│   ├── Financial Due Diligence: doanh thu, EBITDA, dòng tiền, nợ vay, vốn lưu động và chất lượng lợi nhuận.
│   ├── Tax Due Diligence: nghĩa vụ thuế, thanh tra và rủi ro truy thu.
│   ├── Legal Due Diligence: tranh chấp, hợp đồng, giấy phép, sở hữu trí tuệ, lao động và tài sản bảo đảm.
│   ├── Commercial Due Diligence: thị trường, khách hàng, cạnh tranh, sản phẩm và lợi thế kinh doanh.
│   ├── Operational / Technology Due Diligence: nhà máy, hệ thống, dữ liệu, an ninh và khả năng tích hợp.
│   ├── Competition / Merger Control: rà soát nghĩa vụ thông báo tập trung kinh tế và điều kiện cạnh tranh.
│   ├── Foreign Ownership / Sector Rules: giới hạn, điều kiện tiếp cận thị trường và giấy phép chuyên ngành.
│   ├── Related-party / Conflict-of-interest Review: giao dịch liên quan và xung đột lợi ích, đặc biệt trong MBO.
│   ├── Public Tender Offer Compliance: kiểm tra nghĩa vụ chào mua công khai nếu là công ty đại chúng.
│   └── Closing & Post-closing Filings: hoàn tất thanh toán, đăng ký thay đổi, công bố thông tin và thủ tục sau giao dịch.
│
└── 8. POST-ACQUISITION VALUE & EXIT (TẠO GIÁ TRỊ, TÍCH HỢP VÀ THOÁI VỐN)
    ├── Integration: tích hợp nhân sự, quy trình, hệ thống, công nghệ và dữ liệu.
    ├── Governance Reset: thiết lập HĐQT, ban điều hành, quyền phê duyệt và kiểm soát nội bộ.
    ├── Synergy Capture: hiện thực hóa cộng hưởng doanh thu/chi phí.
    ├── Operational Improvement: cải thiện năng suất, biên lợi nhuận và dòng tiền.
    ├── Capital Structure Optimization: tối ưu cấu trúc vốn và khả năng trả nợ.
    ├── Buy-and-Build Expansion: tiếp tục mua bổ sung để mở rộng nền tảng.
    ├── IPO / Relisting: niêm yết hoặc tái niêm yết nếu đáp ứng điều kiện.
    ├── Strategic Sale: bán cho bên mua chiến lược.
    ├── Secondary Buyout: bán cho quỹ PE khác.
    ├── Management Buyback: đội ngũ quản lý mua lại từ sponsor trong giai đoạn sau.
    └── Asset Disposal / Wind-down: bán tài sản hoặc thu hẹp/chấm dứt hoạt động theo phương án hợp pháp.

---

# 1. GIẢI THÍCH CÁC ĐIỂM PHÁP LÝ CẦN HIỆU CHỈNH TRONG BẢNG GỐC

## 1.1. Tỷ lệ sở hữu không đồng nghĩa trực tiếp với quyền lực

- Tỷ lệ vốn/cổ phần chỉ là chỉ báo ban đầu. Quyền thực tế phụ thuộc vào cổ phần có quyền biểu quyết, cổ phần ưu đãi, thỏa thuận cổ đông, điều lệ, tỷ lệ tham dự, ủy quyền, cơ cấu sở hữu phân tán và quy định chuyên ngành.
- “Dưới 5% = không có quyền tham gia” là cách diễn đạt quá tuyệt đối. Cổ đông vẫn có các quyền cơ bản theo loại cổ phần và pháp luật.
- “5%–10% có quyền đề cử” không chính xác theo ngưỡng mặc định của Luật Doanh nghiệp: ngưỡng đề cử HĐQT/BKS là từ 10% cổ phần phổ thông, hoặc tỷ lệ thấp hơn do Điều lệ quy định.
- Ngưỡng 5% có thể làm phát sinh tư cách cổ đông lớn tại công ty đại chúng theo Luật Chứng khoán và một số quyền của cổ đông/nhóm cổ đông theo Luật Doanh nghiệp.

## 1.2. 35% không phải quyền phủ quyết tự động

Đối với một số nghị quyết quan trọng của ĐHĐCĐ công ty cổ phần, quy tắc mặc định tại Điều 148 Luật Doanh nghiệp yêu cầu ít nhất 65% tổng số phiếu biểu quyết của cổ đông tham dự và biểu quyết tán thành; Điều lệ và các trường hợp luật định có thể làm thay đổi cách áp dụng.

Vì vậy:
- Không thể nói mọi cổ đông nắm 35% vốn đều có quyền phủ quyết trong mọi công ty và mọi tình huống.
- Nếu toàn bộ phiếu được tính trong cùng một cơ sở biểu quyết và ngưỡng cần đạt là 65%, nhóm phản đối phải có tỷ lệ **lớn hơn 35%** trong cơ sở phiếu đó để làm cho tỷ lệ tán thành giảm xuống dưới 65%; đúng 35% phản đối vẫn có thể để lại đúng 65% tán thành.
- Tỷ lệ tham dự, quyền biểu quyết của từng loại cổ phần, ngưỡng theo Điều lệ và phương thức lấy ý kiến có thể thay đổi kết quả.

## 1.3. 65% không phải toàn quyền tuyệt đối

Ngưỡng 65% là một ngưỡng biểu quyết cho một số nội dung tại ĐHĐCĐ công ty cổ phần theo luật và Điều lệ áp dụng. Không nên biến nó thành một quy tắc chung cho mọi loại hình doanh nghiệp, mọi nghị quyết hoặc mọi cơ chế quản trị.

## 1.4. Mốc 25%, 35%, 45%, 55%, 65%, 75% trong chào mua công khai

Theo Điều 35 Luật Chứng khoán trong văn bản hợp nhất năm 2026 được tra cứu, một số trường hợp dự kiến mua dẫn đến sở hữu trực tiếp/gián tiếp từ 25% cổ phiếu có quyền biểu quyết của công ty đại chúng trở lên phải chào mua công khai và đăng ký với Ủy ban Chứng khoán Nhà nước; người đã nắm từ 25% trở lên mua tiếp dẫn đến các mốc 35%, 45%, 55%, 65%, 75% cũng thuộc trường hợp luật định, trừ ngoại lệ. Đây là **ngưỡng thủ tục chào mua công khai**, không phải bản thân ngưỡng quyền phủ quyết hay quyền kiểm soát.

## 1.5. 100% cổ phần không đồng nghĩa sáp nhập

- Mua 100% cổ phần/phần vốn thường làm thay đổi chủ sở hữu của pháp nhân mục tiêu; pháp nhân mục tiêu vẫn tồn tại.
- Việc chuyển đổi sang công ty TNHH một thành viên cần căn cứ vào loại hình, số lượng chủ sở hữu/thành viên và thủ tục đăng ký tương ứng; không nên mô tả là tự động xảy ra chỉ vì “mua đứt”.
- Sáp nhập là thủ tục tái tổ chức: công ty bị sáp nhập chuyển toàn bộ tài sản, quyền, nghĩa vụ và lợi ích hợp pháp sang công ty nhận sáp nhập rồi chấm dứt tồn tại theo pháp luật.

## 1.6. Asset Deal không bảo đảm loại bỏ toàn bộ nợ/nghĩa vụ cũ

Asset Deal cho phép xác định phạm vi tài sản được mua, nhưng nghĩa vụ có thể gắn với tài sản, hợp đồng, người lao động, thuế, môi trường, đất đai, giấy phép hoặc quy định chuyển giao bắt buộc. Phải kiểm tra từng nghĩa vụ và cơ chế kế thừa/tiếp nhận; không dùng mệnh đề “không nhận nợ cũ” như quy tắc tuyệt đối.

## 1.7. LBO không đồng nghĩa MBO và không mặc định lấy tài sản Target thế chấp

- **MBO** trả lời “ai mua?” — đội ngũ quản lý hiện tại.
- **LBO** trả lời “mua bằng cấu trúc vốn nào?” — sử dụng nợ đáng kể.
- Một thương vụ có thể đồng thời là MBO + LBO.
- Việc tài sản của Target được dùng để bảo đảm khoản vay phục vụ mua cổ phần phụ thuộc cấu trúc pháp lý, thẩm quyền, lợi ích doanh nghiệp, tài liệu tín dụng, đăng ký bảo đảm và giới hạn pháp luật; không tự động hợp lệ hoặc tự động xảy ra.

## 1.8. Acqui-hire là động cơ, không phải một cấu trúc pháp lý duy nhất

Acqui-hire mô tả mục tiêu mua doanh nghiệp để tiếp nhận nhân tài/đội ngũ. Giao dịch có thể dùng Share Deal, Asset Deal, chuyển giao hoạt động hoặc thỏa thuận lao động phù hợp. Không mặc định mọi nhân viên bị chuyển giao tự động.

---

# 2. DEAL CLASSIFICATION TEMPLATE — MẪU MÃ HÓA MỘT THƯƠNG VỤ

Dùng cấu trúc sau để ghi nhận từng giao dịch:

```text
MUALAI-ID: MA-YYYY-XXX
TARGET: [Tên doanh nghiệp / tài sản / đơn vị kinh doanh]
ACTOR: [Insider / Management / Founder / Strategic Buyer / PE Sponsor / Consortium]
OWNERSHIP-BEFORE: [Tỷ lệ và loại quyền trước giao dịch]
OWNERSHIP-AFTER: [Tỷ lệ và loại quyền sau giao dịch]
CONTROL: [Minority / Significant Influence / Blocking Potential / Majority / Supermajority / Full]
STANCE: [Friendly / Hostile / Unsolicited / Contested]
TARGET-PERIMETER: [Share Deal / Asset Deal / Division / Subsidiary / Debt / IP / Merger]
BUYOUT-TYPE: [MBO / MBI / BIMBO / EBO / LBO / IBO / Secondary / Distressed / Other]
FINANCING: [Equity / Debt / Mezzanine / Seller Note / Rollover / Mixed]
CONSIDERATION: [Cash / Shares / Mixed / Earn-out / Other]
STRATEGIC-MOTIVE: [Expansion / Synergy / Vertical Integration / Technology / Talent / Turnaround / Other]
GOVERNANCE-AFTER: [Board / Management / Sponsor / Shareholder Agreement]
REGULATORY: [Approvals / Tender Offer / Competition / Foreign Ownership / Sector Rules]
VALUE-CREATION: [Cash Flow / Margin / Growth / Synergy / Debt Paydown / Other]
EXIT-PATH: [Strategic Sale / Secondary Buyout / IPO / Other]
EVIDENCE-STATUS: [Verified / Partially Verified / Unverified]
```

**Ví dụ phân loại:** Quản lý hiện tại cùng một quỹ PE mua toàn bộ cổ phần công ty, sử dụng vốn chủ và nợ:
- ACTOR: Management + PE Sponsor
- BUYOUT-TYPE: Sponsor-backed MBO + LBO
- TARGET-PERIMETER: Share Deal
- OWNERSHIP-AFTER: 100%
- CONTROL: Full
- FINANCING: Equity + Debt
- STANCE: Friendly hoặc Hostile tùy sự đồng thuận thực tế

Không suy ra stance, mức đòn bẩy hay pháp lý chỉ từ tên thương vụ.

---

# 3. M&A / BUYOUT PROCESS — VÒNG ĐỜI GIAO DỊCH

1. **Thesis & Screening:** xác định lý do mua, tiêu chí mục tiêu và khả năng tạo giá trị.
2. **Target Identification:** lập danh sách mục tiêu, chủ sở hữu và bên có quyền quyết định.
3. **Initial Approach / NDA:** tiếp cận, ký bảo mật và trao đổi thông tin sơ bộ.
4. **Indicative Offer / LOI:** đề xuất sơ bộ, định giá chỉ dẫn và điều khoản chính.
5. **Due Diligence:** thẩm định tài chính, pháp lý, thuế, thương mại, vận hành, nhân sự và công nghệ.
6. **Valuation & Financing:** thống nhất giá trị doanh nghiệp, giá trị vốn chủ, nguồn vốn và cấu trúc thanh toán.
7. **Definitive Agreements:** đàm phán SPA/APA/Merger Agreement, bảo đảm, bồi thường và điều kiện tiên quyết.
8. **Regulatory & Corporate Approvals:** phê duyệt nội bộ, chào mua công khai, cạnh tranh, đầu tư và giấy phép nếu áp dụng.
9. **Signing → Closing:** ký giao dịch, hoàn thành điều kiện, thanh toán và chuyển giao.
10. **Post-closing Integration:** tích hợp, quản trị, xử lý cam kết và hiện thực hóa kế hoạch tạo giá trị.
11. **Exit / Reinvestment:** thoái vốn, bán lại, IPO, secondary buyout hoặc tiếp tục nắm giữ.

---

# 4. MASTER MODEL — CÔNG THỨC TƯ DUY

Một thương vụ MUALAI được mô tả bằng vector phân loại:

`M = (A, T, O, C, S, F, P, G, V, E)`

Trong đó:
- `A` — Actor: người mua.
- `T` — Target: đối tượng mua.
- `O` — Ownership: tỷ lệ và loại quyền sở hữu.
- `C` — Control: quyền biểu quyết/quản trị thực tế.
- `S` — Stance & Structure: mức độ đồng thuận và hình thức giao dịch.
- `F` — Financing: nguồn vốn và cấu trúc nợ/vốn chủ.
- `P` — Purpose: động cơ chiến lược.
- `G` — Governance: quản trị sau giao dịch.
- `V` — Value Creation: cơ chế tạo giá trị.
- `E` — Exit: phương án thoái vốn/kết thúc vòng đời đầu tư.

**Nguyên tắc:** các trục độc lập nhưng có quan hệ. Ví dụ một thương vụ có thể là MBO về người mua, LBO về tài trợ, Share Deal về đối tượng, Friendly về mức độ đồng thuận và Full Acquisition về tỷ lệ sở hữu.

---

# 5. QUALITY-CONTROL CHECKLIST

- [ ] Xác định đúng người mua cuối cùng và chủ sở hữu hưởng lợi cuối cùng.
- [ ] Phân biệt người mua nội bộ với người mua bên ngoài.
- [ ] Xác định đối tượng là cổ phần, tài sản, đơn vị kinh doanh, khoản nợ hay IP.
- [ ] Kiểm tra tỷ lệ sở hữu theo cổ phần có quyền biểu quyết, không chỉ theo vốn danh nghĩa.
- [ ] Phân biệt quyền sở hữu, quyền biểu quyết, quyền đề cử và quyền điều hành.
- [ ] Kiểm tra Điều lệ, thỏa thuận cổ đông, cổ phần ưu đãi và người có liên quan.
- [ ] Xác định nghĩa vụ chào mua công khai nếu mục tiêu là công ty đại chúng.
- [ ] Phân tích nợ, nghĩa vụ tiềm ẩn và phạm vi trách nhiệm trong Share Deal/Asset Deal.
- [ ] Kiểm tra nguồn vốn, tài sản bảo đảm, bảo lãnh và khả năng trả nợ.
- [ ] Xác định điều kiện phê duyệt cạnh tranh, đầu tư, ngoại hối, đất đai và ngành nghề.
- [ ] Xác định thời điểm chuyển quyền, Closing và đăng ký sau giao dịch.
- [ ] Có kế hoạch quản trị, tích hợp và tạo giá trị sau mua.

---

# 6. GLOSSARY — THUẬT NGỮ CỐT LÕI

- **Acquisition:** mua lại/tiếp nhận.
- **Buyout:** mua lại toàn bộ hoặc phần đủ để thiết lập quyền kiểm soát.
- **Takeover:** thâu tóm/tiếp quản quyền kiểm soát.
- **MBO:** Management Buyout — quản lý hiện tại mua lại.
- **MBI:** Management Buy-in — quản lý bên ngoài mua lại.
- **BIMBO:** Buy-in Management Buyout — kết hợp quản lý hiện tại và bên ngoài.
- **EBO:** Employee Buyout — người lao động mua lại.
- **LBO:** Leveraged Buyout — mua lại có sử dụng đòn bẩy nợ.
- **IBO:** Institutional Buyout — tổ chức đầu tư dẫn dắt mua lại.
- **PE:** Private Equity — vốn cổ phần tư nhân.
- **Sponsor:** nhà tài trợ/quỹ dẫn dắt giao dịch.
- **BidCo / NewCo:** pháp nhân/phương tiện được lập để thực hiện giao dịch.
- **Target:** doanh nghiệp mục tiêu.
- **Share Deal:** mua cổ phần/phần vốn.
- **Asset Deal:** mua tài sản.
- **Tender Offer:** chào mua công khai.
- **Friendly Takeover:** thâu tóm có sự đồng thuận.
- **Hostile Takeover:** thâu tóm trong tình huống ban lãnh đạo mục tiêu phản đối.
- **Carve-out:** tách một đơn vị khỏi doanh nghiệp mẹ để giao dịch.
- **Secondary Buyout:** quỹ PE bán doanh nghiệp cho quỹ PE khác.
- **Acqui-hire:** mua doanh nghiệp chủ yếu để tiếp nhận nhân tài/đội ngũ.
- **Due Diligence:** thẩm định trước giao dịch.
- **Signing:** thời điểm ký hợp đồng giao dịch.
- **Closing:** thời điểm hoàn tất các điều kiện và thực hiện chuyển giao/thanh toán theo hợp đồng.
- **Earn-out:** khoản thanh toán bổ sung phụ thuộc điều kiện/kết quả tương lai.
- **Rollover Equity:** phần vốn người bán/nhà quản lý tiếp tục giữ hoặc tái đầu tư.
- **Synergy:** giá trị cộng hưởng giữa bên mua và doanh nghiệp mục tiêu.

---

# 7. SOURCE REGISTER & RELIANCE NOTE

Các văn bản dưới đây được dùng để hiệu chỉnh những điểm pháp lý Việt Nam trong bản taxonomy. Khi dùng cho một giao dịch thật, cần mở bản văn bản chính thức, kiểm tra tình trạng hiệu lực, văn bản sửa đổi mới nhất, điều lệ mục tiêu và ý kiến chuyên môn phù hợp.

1. **Luật Doanh nghiệp — Văn bản hợp nhất 67/VBHN-VPQH ngày 15/08/2025.** Các điểm được đối chiếu: Điều 115 (quyền cổ đông phổ thông; mốc 5% và 10%), Điều 147–148 (hình thức và ngưỡng thông qua nghị quyết ĐHĐCĐ), quy định về chuyển đổi, sáp nhập và tổ chức lại doanh nghiệp. Ưu tiên bản đăng Công báo.  
   https://congbao.chinhphu.vn/van-ban/van-ban-hop-nhat-so-67-vbhn-vpqh-45865.htm

2. **Luật sửa đổi, bổ sung một số điều của Luật Doanh nghiệp — Luật số 76/2025/QH15.** Ban hành ngày 17/06/2025, hiệu lực từ 01/07/2025; là một trong các văn bản đã được hợp nhất vào VBHN 67/VBHN-VPQH.  
   https://vanban.chinhphu.vn/?classid=1&docid=214562&orggroupid=1&pageid=27160

3. **Luật Chứng khoán — Văn bản hợp nhất 102/VBHN-VPQH ngày 22/04/2026.** Các điểm được đối chiếu: định nghĩa cổ đông lớn từ 5% cổ phiếu có quyền biểu quyết; Điều 35 về các trường hợp chào mua công khai; nghĩa vụ công bố thông tin.  
   https://vbpl.freshdesk.com/support/solutions/articles/16000237353-c%C3%B4ng-v%C4%83n-102-vbhn-vpqh-ng%C3%A0y-22-04-2026-h%E1%BB%A3p-nh%E1%BA%A5t-lu%E1%BA%ADt-ch%E1%BB%A9ng-kho%C3%A1n

4. **SEC Investor.gov — Tender Offer.** Tài liệu nền tảng để phân biệt chào mua công khai do bên thứ ba thực hiện với issuer tender offer do chính tổ chức phát hành thực hiện; quy tắc Hoa Kỳ không thay thế luật Việt Nam.  
   https://www.investor.gov/introduction-investing/investing-basics/glossary/tender-offer

5. **Cập nhật lập pháp:** Bộ Tài chính đã đăng hồ sơ chính sách/dự thảo về Luật Doanh nghiệp sửa đổi vào tháng 11/2026. Hồ sơ đề xuất/dự thảo không tự nó là luật đã có hiệu lực; cần kiểm tra văn bản được Quốc hội thông qua và ngày hiệu lực trước khi áp dụng.  
   https://www.mof.gov.vn/bo-tai-chinh/dong-gop-y-kien-du-thao-van-ban/ho-so-chinh-sach-luat-doanh-nghiep-sua-doi

**Reliance note:** Đây là tài liệu phân loại và học tập, không phải ý kiến pháp lý, định giá, thuế hay khuyến nghị đầu tư. Ngưỡng phần trăm trong sơ đồ là taxonomy phân tích; chỉ các ngưỡng được ghi rõ là quy định luật mới được hiểu là ngưỡng pháp lý, và vẫn phải đọc kèm điều kiện/ngoại lệ. Pháp luật có thể tiếp tục được sửa đổi sau ngày lập bản này; cần kiểm tra lại tình trạng hiệu lực tại thời điểm giao dịch.

---

**END — THH-MUALAI-v1.0.0**
