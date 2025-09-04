Implementé tres modelos preentrenados (VGG16, ResNet50 y DenseNet121) usando transferencia de aprendizaje. Congelé las capas convolucionales y entrené únicamente la cabeza densa para clasificar tres clases de pulmón:

lung_n → Tejido sano

lung_aca → Adenocarcinoma

lung_scc → Carcinoma de células escamosas

El conjunto de validación es 15% del total.
