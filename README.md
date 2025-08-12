
> Sistema de Machine Learning que predice la cancelación de clientes (churn) con **84% de precisión**, permitiendo retener hasta **$810K anuales**.

## 📊 Resultados

| Modelo | ROC AUC | Recall | Precision | Accuracy |
|--------|---------|--------|-----------|----------|
| **Random Forest** ⭐ | **84.0%** | **72.2%** | **56.7%** | **78.0%** |
| Logistic Regression | 84.2% | 79.7% | 52.0% | 75.1% |

**💰 Impacto:** Detecta 1,350 clientes en riesgo anualmente, salvando $810K en revenue.

## 🛠️ Tech Stack

- **Python 3.8+** | **pandas** | **scikit-learn** | **imbalanced-learn**
- **SMOTE** para balanceo | **GridSearchCV** para optimización
- **Pipeline automatizado** | **Cross-validation 5-fold**

## 🔍 Key Insights

### Top 5 Factores de Churn:
1. **👥 tenure** - Clientes nuevos (<6 meses) = Alto riesgo
2. **💰 TotalCharges** - Alto valor paradójicamente aumenta riesgo
3. **📋 Contract_Two year** - Contratos largos reducen churn 80%
4. **🌐 Fiber Optic** - Correlaciona con mayor churn
5. **💳 Electronic Check** - Método de pago problemático

### Estrategias Recomendadas:
- 🎯 **Programa retención temprana** (0-6 meses): 20% descuento
- 📋 **Migrar a contratos 2 años**: 2 meses gratis + precio fijo
- 🌟 **Programa VIP**: Descuentos escalonados para alto valor
- 💳 **Migrar métodos pago**: $20 descuento por cambio a débito automático

