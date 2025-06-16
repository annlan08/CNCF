# CNCF
CNCF 的專案內容

+ argo cd => 是一套 GitOps 工具，用於自動化 Kubernetes 應用的部署與同步 
  (可以想像用 Git 分支觸發 K8s 部屬，在 CD 環節有這個功能十分方便)
  外加有很棒的 UI 介面
  
+ Istio => 提供服務網格功能，包括服務發現、流量控制、觀測與安全機制
  (不過我這邊用到的主要是 Istio 的 Ingress Gateway ， 作為 K8S 叢集的統一入口)
  
+ Prometheus (搭配 grafana 作為 UI) => 用於收集與查詢系統與應用層級的 metrics，可協助識別效能瓶頸與資源異常

+ OpenTelemetry => 可觀測性(observability)的標準化工具集，可以支援 logs、metrics、traces
  另外特別提到是剛好 RabbitMq  跟他有完整的整合支援

+ Helm/Helm chart => 
	Kubernetes 的套件管理工具，使用 Helm Chart 將部署資源模板化、參數化，使應用部署檔案可觀性更加
	算是一種用較人類友善的方式寫 k8s deploy 檔案的方式

+ Harbor => 更 Docker Hub 很像都屬於 image repository，不過會由 cncf 基金會支持該軟體發展
